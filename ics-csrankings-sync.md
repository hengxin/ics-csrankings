# ics-csrankings-sync

## [Configuring a `remote` for a fork](https://help.github.com/en/articles/configuring-a-remote-for-a-fork)

- `git remote add upstream https://github.com/emeryberger/CSrankings.git`

You must configure a remote that points to the upstream repository in Git 
to *sync changes you make in a fork with the original repository*. 
This also allows you to *sync changes made in the original repository with the fork*.

## [Syncing a fork](https://help.github.com/en/articles/syncing-a-fork)

- `git checkout upstream/gh-pages`: 
- `git fetch upstream`
Fetch the branches and their respective commits from the upstream repository.
- `git checkout gh-pages`
Check out your fork's local `gh-pages` branch.
- `git merge upstream/gh-pages`
Merge the changes from `upstream/gh-pages` into your local `gh-pages` branch. 

## [Make pull requests]()
