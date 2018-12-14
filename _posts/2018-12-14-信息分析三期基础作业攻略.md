---
layout:     post
title:      信息分析三期基础作业攻略
subtitle:   具备上帝视角的方法论
date:       2018-12-14
author:     Hu Feng
header-img: img/christianity-cross-god-54333.jpg
catalog: true
tags:
    - cognitive science
    - Information Analysis
    - ACH
---

# 信息分析三期基础作业攻略

参加此次课程的首要目标就是认真完成基础作业和进阶作业，首先就每个问题的处理过程做简要记录，再做整体的总结。

## 习题详解

将20个问题根据考察的主题归为9类，以下为详细内容：

- 问题1/问题15:全局认识

考察构建最小全局认识，课程推荐的最小框架是：时间、空间和变量关系。

问题1:涉及这个内容的课件在：Ch1 信息分析概论-课程设计理念-课程理念说明

课件中的对应图片是：

![](https://static.openmindclub.com/openmindclub/2018-10-01-PicIA002CH1Yang%20.005.jpeg)

问题15:考察全局认识的四个方面：

![](https://static.openmindclub.com/openmindclub/2018-10-01-PicIA002CH1Yang%20.046.jpeg)

本题不涉及`伦理道德`，故选ABD。

- 问题2:洛特卡定律

考察洛特卡定律，发表n篇文章的作者数量是发表1篇文章作者数量的1/n^2,当写50篇文章的作者数为200时，发表1篇文章的作者数为：
```
200 * 50^2 = 500000
```
根据洛特卡定律，发表1篇文章的作者占某领域作者总数的60.79%，故该领域作者总数为：

```
500000 / 60.69% = 822503

如果将60.79%约等于60%，则
500000 / 60% = 833333
```
- 问题3:普赖斯定律

考察普赖斯定律，有两个公式：

![普赖斯公式](http://www.jinhuaji.net/hufeng/document/photo.hf.com/image%E6%99%AE%E8%B5%96%E6%96%AF%E5%85%AC%E5%BC%8F.png)

    - 核心著者发表论文数为：

0.749 * &radic;112 = 7.926 

    - 核心著者的单篇被引量为：

0.749 * &radic;28224 = 125.832 

答案取8､126,选C

上面公式的链接为：

[基于普赖斯定律和综合指数法的核心著者测评](http://www.cjstp.cn/cjstp/ch/reader/create_pdf.aspx?file_no=20161214&year_id=2016&quarter_id=12&falg=1)

- 问题4:布拉德福定律

根据布拉德福定律，核心期刊、相关期刊和外围期刊的数量比例为：

$$ 1 ：n : n ^ 2 $$

上面的n就是布拉德福常数

当外围一区（**即相关期刊**）数为200时，核心期刊数为：

$$ 200 / 5 = 40 $$

二区期刊（**即外围期刊**）数为：

$$ 40\times 5^2 = 1000 $$

选C

- 问题5/问题6/问题7:精确搜索

考察精确搜索的方式：

|序号|功能|语法|
|:----:|------------|:-------------------:|
|1|普通搜索|主题词
|2|准确搜索|“主题词”
|3|文章标题中含主题词|intitle:"主题词"
|4|特写网页中搜主题词|site:url
|5|正文搜索|intext:"主题词" 
|6|url搜索|inurl:
|7|指定文件类型|filetype:如pdf/ppt等
|8|模糊匹配|使用*

    - 问题5:intext:"文化战略"
    - 问题6:site:www.sipo.gov.cn filetype:pdf
    - 问题7:第*届挑战杯课外学术科技作品竞赛结果

- 问题8/问题9/问题10/问题16/问题19/问题20:布尔搜索及综合运用

> 考察布尔搜索的语法：
- AND:交集
- OR：并集
- NOT：剔除

问题8:“东北 or 黑龙江 or 吉林”范围最大，故选B。

问题9:AU=author(作者）;JN=journal（期刊）;SU=subject（主题）;AB=abstract（摘要）
![](http://cardstatic.openmindclub.com//18-4-22/11046421.jpg)
选D。

问题10:OR的作用选C。

问题16/问题19/问题20:综合了上述搜索的技巧。

- 问题11:RSS

OPML（英语：Outline Processor Markup Language）意为“大纲处理标记语言”，是一种基于XML上的文件保存格式。目前流行的应用方式为收集博客或播客的RSS来源，整理成单一可交换的OPML格式的订阅列表，让用户便于转移自己的订阅项目。

答案是B。

- 问题12/问题13/问题17/问题18:Zotero

**考察Zotero的优点、原理及使用技巧。**

问题12我的回答：C. 在 My Library 中按时间排序查看最新一周条目 错误
正确答案为：A. 利用高级搜索建立相应查询并保存该查询
> 答案解析：内置高级搜索,相当于建立了一个动态文件夹,会不断更新条目。方式 ABD 均需要人工识别分类,不够优雅。考虑一个方式是否足够优雅,可以思考这个方法在更长时间、更高量级是否依然可持续?例如在这个情境下,可以思考 10 年后我是否能够依旧使用方式 ABCD ,它们会遇到什么问题?假设每周只需要处理 20 篇变成 200 篇 2000 篇,方式 ABCD 会遇到什么问题?这样不同处理方式高下立见。

同理，问题17的选项B也是这个内容。

问题13:在Zotero 安装路径查看有哪些translators，选B。

问题18:Zotero基于元数据命名，不基于主题分类。这是**反常识**的一点。

- 问题14:图片EXIF

获取图片EXIF元数据的操作步骤：

1. 点击chrome浏览器`视图-开发者-显示原代码`；
2. 使用 `command+F `关键词image或jpg，搜索到`http://cardstatic.openmindclub.com/InfoAnalysis/ia003textpic.jpg`，然后下载原图片，文件名为:`ia003textpic.jpg`；
3. 在`https://exif.tuchong.com/`点击`选择文件`，选择`ia003textpic.jpg`打开，得到图片的元数据信息：

![](http://www.jinhuaji.net/hufeng/document/photo.hf.com/imageexif-of-photo.png)

## 实践总结及待完成工作

1. 怎样去除EXIF信息

    - 手机APP

    在应用商品搜`EXIF`，能找到很多款APP，苹果多为应用内付费。

    - Macbook

    在App Store里搜索`EXIF`，就能找到多款软件。

1. 安装了Tabs outliner与Sidewise，但还没体会到这两款插件的好处，需继续探索使用。

2. Zotero只有300M免费存储，课程推荐使用Icloud，可否使用七牛云？待我继续破解。

---
**Zotero是一款强大的知识管理工具，通过对信息的元数据进行综合搜索分析，让普通人具备了上帝视角，更易看到现状的不足，指出创新的方向。**

## CHANGELOG

- 2018.12.14 补充修改于于上海回北京的高铁
- 2018.12.13 胡峰创建于北京至上海的高铁
