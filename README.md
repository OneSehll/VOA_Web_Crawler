# VOA_Web_Crawler
## Hello!
这是从刚开始学爬虫就开始做的项目了吧，断断续续差不多两年把这个东西弄好，放在这儿留个纪念
## Content
[TOC]

### Intro
通过爬虫获取[51VOA常速英语](http://www.51voa.com/VOA_Standard_English/)的当日文章并存放在docx文档
### Requirements
需要下面几个Python的包，其中遇见什么安装的问题自行百度或者科学上网解决
 - urllib 用来打开链接和下载MP3
 - [Python-docx](http://python-docx.readthedocs.io/en/latest/)
  用来保存到docx文档
 - os 创建文件夹
 - re 正则表达式，筛选网页内容
 - time 日期格式
### Installation
通过virtualenv创建虚拟环境后，在github下载这个项目，具体的目录树如下:
```
Scrapy
├── bin
├── include
├── lib
├── pip-selfcheck.json
├── VOA_Web_Crawler
└── share

5 directories, 1 file
```
具体安装步骤如下：
```
virtualenv Scrapy -p python3
cd Scrapy
git clone git@github.com:OneSehll/VOA_Web_Crawler.git
```

然后安装上面提到的Python库
OK！Good Luck！
- 
