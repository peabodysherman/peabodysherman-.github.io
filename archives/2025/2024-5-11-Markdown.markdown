---
layout: post
title: "Markdown"
description: "Markdown入门指南，Markdown语法，Markdown优点"
categories: doc
tags: [doc, Markdown]
---
#目录
1. 什么是Markdown
2. Markdown优点
3. Markdown语法
4. else

#什么是Markdown
- Markdown 是一种简单的、轻量级的标记语法
- Markdown 的目标是实现「易读易写」
- Markdown 让我们专注写作，而不是关注排版

下面是一段Markdown栗子:

    ##第三章 “水果”公司的复兴(乔布斯和苹果公司)
    &emsp;&emsp;看过汤姆·汉克斯主演的电影 [《阿甘正传》][1] 的读者,也许还记得那么一个镜头。傻人有傻 福的阿甘最后捧着一张印有苹果公司标志的纸说,我买了一个水果公司的股票,有人说我这 一辈不用再为钱发愁了。那是九十年代初的电影,导演挑中了苹果公司,因为它的股票确实 在几年间涨了十倍。

    [1]: http://vip.iqiyi.com/20110805/d768b392b9ec5d37.html

显示出来效果是酱紫的:

##第三章 “水果”公司的复兴(乔布斯和苹果公司)
&emsp;&emsp;看过汤姆·汉克斯主演的电影 [《阿甘正传》][1] 的读者,也许还记得那么一个镜头。傻人有傻 福的阿甘最后捧着一张印有苹果公司标志的纸说,我买了一个水果公司的股票,有人说我这 一辈不用再为钱发愁了。那是九十年代初的电影,导演挑中了苹果公司,因为它的股票确实 在几年间涨了十倍。

[1]: http://vip.iqiyi.com/20110805/d768b392b9ec5d37.html

怎么样，是不是比HTML写起来爽很多，感觉萌萌哒

#Markdown 优点
- 纯文本，便于编辑和传播
- 可读性好
- 应用广泛，在 GitHub, Reddit, StackOverflow 等一大批网站的影响下，在互联网上应用很广
- 她设计的初衷就是让写字的人专注于写字，用纯文本简单的符号标记格式，最后再通过工具转换成鬼畜的HTML

#Markdown 语法

## 1. 标题
语法：

    This is an H1
    =============

    This is an H2
    -------------

    # This is an H1

    ## This is an H2

    ###### This is an H6

预览：

This is an H1
=============

This is an H2
-------------

# This is an H1

## This is an H2

###### This is an H6

## 2. 粗体，斜体
语法：

    **粗体**
    *斜体*

预览：

**粗体**
*斜体*

## 3. 列表 
语法：

    - 无序列表项目
    - 无序列表项目
    - 无序列表项目

    1. 有序列表项目
    2. 有序列表项目
    3. 有序列表项目

预览：

- 无序列表项目
- 无序列表项目
- 无序列表项目

1. 有序列表项目
2. 有序列表项目
3. 有序列表项目

## 4. 引用
语法：

    > 引用的文字
    > 引用的文字
    > 引用的文字

预览：

> 引用的文字
> 引用的文字
> 引用的文字

## 5. 图片和链接
语法：

    [github](https://github.com)

    ![avatar](https://avatars0.githubusercontent.com/u/3368034)

预览：

[github](https://github.com)

![avatar](https://avatars0.githubusercontent.com/u/3368034)


## 6. 代码
行内引用代码使用反引号 ` ，代码块使用Tab缩进

语法：

    `var a = 1;`

    `Tab`//Tab或四个空格（大段文字添加代码框，每行前添加）
    `Tab`var a = 1;
    `Tab`var b = 2;

预览：

`var a = 1;`

    //Tab或四个空格（大段文字添加代码框，每行前添加）
    var a = 1;
    var b = 2;

## 7. 缩进 
写文档时，我们常常希望能够首行缩进，可以加入&ensp;来输入一个空格.加入&emsp;来输入两个空格
语法：

    &ensp;这里缩进一个空格

    &emsp;这里缩进两个空格

预览：

&ensp;这里缩进一个空格

&emsp;这里缩进两个空格

## 8. 表格
语法：

    ABCD | EFGH | IGKL
    -----|------|----
    a    | b    | c
    d    | e    | f
    g    | h    | i

预览：

ABCD | EFGH | IGKL
-----|------|----
a    | b    | c
d    | e    | f
g    | h    | i

## else
1. 中英文切换问题，每次切换很麻烦

设置自定义短语
![custom](/img/custom.png)


### 参考资源

1. [与所有的推动人类进程的发明不同，这是一件纯粹个人的劳动成果](http://coolshell.cn/articles/11928.html)
2. http://www.jianshu.com/p/468f111d8fd3
