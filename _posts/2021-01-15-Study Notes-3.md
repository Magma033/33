---
title: HTML的基本结构及如何加阴影
excerpt_separator: "<!--more-->"
categories: 
  - 学习笔记
---
## 一起来了解一些html吧！

<!--more-->

## HTML结构
HTML网页是静态的HTML纯语言，通过服务器处理才能呈现出客户浏览的页面。完整的HTML包括！DOCTYPE文档头声明、head标签，title标题、
body标签、字符编码


<!DOCTYPE html>！(文档头声明，让浏览器知道以什么版本的HTML写的以下代码),<html lang="en">(文档语言),<head>(头部声明),<meta charset="utf-8" />(!文档头声明，让浏览器知道以什么字符编号写的代码),<title>我是标题</title>,</head>,<body>我是身体，正文写在这里</body>,</html>


## 注意事项
- html标签要成对出现，结束时需要加斜杠，，例如<html></html>，头部标签<head></head>，主体标签是<body></body>
- head中的内容无法在浏览器页面显示给用户观看
- body是主题，其内容一般在浏览器页面呈现给用户看
- meta元素可以插入其他元素，用来标记搜索引擎要在你页面读取的关键词


## 其他标签

- b粗体

- i斜体

- s删除线
- <h1><h2><h3><h4><h5><h6>（字体大小是从大到小)
- title是文档标题，<h>是文字标题
- br是换行
- p是段落
- u是下划线

## 添加阴影
在页面中的文字、图片或盒子添加阴影，可以增强立体感，给用户一个良好的视觉体验。

## 文字阴影

h1 {text-shadow:2px 2px #FF0000;}

三个值分别为偏移值、模糊程度、色值

## 盒子阴影

---
div
{

box-shadow: 10px 10px 5px #888888;
}

---

四个值分别为X轴偏移，Y轴偏移，模糊程度，色值








