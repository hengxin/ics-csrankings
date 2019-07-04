# ics@csrankings 

## csrankings 是什么?
csrankings 是针对世界范围内的cs机构(看它的数据,是以学校为单位的)的排行榜。它不使用引用数作为排名指标，而(目前的粗糙理解)更关注发表在高质量会议/期刊上的论文数量。论文数据的来源是 DBLP。

## 我们需要做什么?
我们需要向 `csrankings` 数据库中添加 `faculty members`。

`csrankings` 对 `faculty members` 的要求如下:
`Eligible faculty include only full-time, tenure-track faculty members 
on a given campus who can solely advise PhD students in Computer Science.`

我的理解是: 只允许添加博士生导师。
我到计算机系主页查了一下, 我们需要添加/核对的教师信息包括:
吕建、陶先平、马晓星、许畅、徐锋、黄宇。

*注:* 我咨询了俞扬老师。俞老师说, 看官网上的说明, 好像是只允许添加博士生导师的信息。不过, 添加其他教师的信息似乎也是可以的。
我目前整理的信息，还没有包含我们所有教师。

## 添加什么信息?
csrankings 要求提供按如下格式提供信息:
`name,affiliation,homepage,scholarid`
- `name`: 在 dblp 上的姓名 (如有需要, 添加去重编号后缀, 如 `0001`)
- `affiliation`: 对我们来说, 统一为 Nanjing University
(State Key Laboratory for Novel Software Technology, Nanjing University, China (http://cs.nju.edu.cn/))
- `homepage`: 个人主页
- `scholarid`: google scholar id, 就是 google scholar 页面链接中的 `user=` 域

## 具体信息是什么?
### 数据库中已有:

吕建:
Jian Lu 0001,Nanjing University,https://cs.nju.edu.cn/yuhuang,go8RGMkAAAAJ
Jian Lv 0001,Nanjing University,https://cs.nju.edu.cn/yuhuang,go8RGMkAAAAJ
Jian Lü 0001,Nanjing University,https://cs.nju.edu.cn/yuhuang,go8RGMkAAAAJ
更正 (homepage 有误; google scholar id 有误)
Jian Lu 0001,Nanjing University,NOSCHOLARPAGE (未查到 homepage, 未查到 google scholar 页面)
(使用系主页介绍页面: http://cs.nju.edu.cn/58/2a/c2639a153642/page.htm)

陶先平:
Xianping Tao,Nanjing University,http://moon.nju.edu.cn/people/xianpingtao,F3mGYVoAAAAJ
更正 (原 moon.nju.edu.cn homepage 已重定向到 ics.nju.edu.cn)
Xianping Tao,Nanjing University,http://ics.nju.edu.cn/people/xianpingtao,F3mGYVoAAAAJ

马晓星:
Xiaoxing Ma,Nanjing University,http://moon.nju.edu.cn/people/xiaoxingma,44WpWR4AAAAJ
更正 (原 moon.nju.edu.cn homepage 已重定向到 ics.nju.edu.cn)
Xiaoxing Ma,Nanjing University,http://ics.nju.edu.cn/people/xiaoxingma,44WpWR4AAAAJ

许畅:
Chang Xu 0001,Nanjing University,https://cs.nju.edu.cn/changxu,trs4zioAAAAJ
更正 (google scholar id 有误):
Chang Xu 0001,Nanjing University,https://cs.nju.edu.cn/changxu,jlZOlxIAAAAJ

### 数据库中待添加:
徐锋:
- [已提交PR] [已提交Issue] 
Feng Xu 0007,Nanjing University,http://ics.nju.edu.cn/people/fengxu,Fw3wFocAAAAJ
https://scholar.google.com/citations?hl=en&user=Fw3wFocAAAAJ
黄宇:
- [已提交PR] [已提交Issue] 
Yu Huang 0002,Nanjing University,https://cs.nju.edu.cn/yuhuang,UWquqLIAAAAJ
https://scholar.google.com/citations?hl=en&user=UWquqLIAAAAJ

### 待确定是否添加:
胡昊:
Hao Hu 0001,Nanjing University,NOSCHOLARPAGE (未查到homepage, 未查到 google scholar页面)

曹春:
- [已提交PR] [已提交Issue] 
Chun Cao,Nanjing University,https://ccao.cc/en,U08cMmAAAAAJ
https://scholar.google.com/citations?hl=en&user=U08cMmAAAAAJ

余萍:
Ping Yu 0002,Nanjing University,http://ics.nju.edu.cn/people/pingyu,NOSCHOLARPAGE (未查到 google scholar 页面)

### 助理研究员信息
马骏:
Nanjing University,http://ics.nju.edu.cn/people/junma,NOSCHOLARPAGE (未查到精确 dblp 页面; 未查到 google scholar 页面)

汪亮:
- [已提交PR] [已提交Issue] 
Liang Wang 0006,Nanjing University,http://cs.nju.edu.cn/wangliang,O6EwhtYAAAAJ
https://scholar.google.com/citations?hl=en&user=O6EwhtYAAAAJ

姚远:
- [已提交PR] [已提交Issue]
Yuan Yao 0001,Nanjing University,http://cs.nju.edu.cn/yuanyao/index.htm,vUvt8JYAAAAJ
https://scholar.google.com/citations?hl=en&user=vUvt8JYAAAAJ

魏恒峰:
- [已提交PR] [已提交Issue]
Hengfeng Wei,Nanjing University,http://www.bigoh.net/wiki/index.php/user:Hengfeng-Wei,HK9-98EAAAAJ
https://scholar.google.com/citations?hl=en&user=HK9-98EAAAAJ

徐经纬:
Nanjing University,http://ics.nju.edu.cn/people/jingweixu,15maGTwAAAAJ (未查到精确 dblp 页面)

蒋炎岩:
- [已提交PR] [已提交Issue]
Yanyan Jiang 0001,Nanjing University,http://ics.nju.edu.cn/~jyy,4HxZiEcAAAAJ
https://scholar.google.com/citations?hl=en&user=4HxZiEcAAAAJ

秦逸:
Nanjing University, (未查到精确 dblp 页面, 未查到 homepage, 未查到 google scholar 页面)

## 如何添加信息?
- [ ] 我依照官网以及俞扬老师编写的说明向csrankings仓库提交 pull requests 与 issues

## 分数计算方法
计算某机构在单一领域的分值:
- 统计每位 faculty 发表在高水平会议/期刊上的文章数 (# Pubs.)
- 为每位 faculty 计算分值 (称为 Adjusted Counts; Adj. #)
  - sum(foreach paper in Pubs : 1 / # of coauthors)
- 为该机构计算分值 (Geometric Mean Count; Count)
  - sum(foreach faculty in institution : adjusted count for faculty) + 1

计算某机构在多个领域的综合分值:
- 设对每个领域 a1, a2, ..., an, 该机构对应分值为 c1, c2, ..., cn,
则, 该机构在这n个领域的综合分值是 ((c1 + 1) (c2 + 1) ... (cn + 1)) 的 n 次方根
