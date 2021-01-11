---
layout: page
title: 在制作Jekyll网站时遇到的一些问题
excerpt_separator: "<!--more-->"
categories:
     - 学习笔记
---

####  关于Jekyll网站那些事

<!--more-->

### 关于图片
- 在网上下载图片时，要注意看看图片的格式，一些格式对Jekyll网站的搭建是不支持的，比如Webp格式，对Jpg格式与png格式是支持的。对于图片的命名，要有意义，不能是数字数字或字母，图档的命名含有语意如 "banner_homepage" 为正确，纯数字123或字母abc序号丶或者仅尺寸如300x200等档名为错。
- 图片路径要对应
 
### 使文章显示出来 
1.
---
layout: page

title: 
excerpt_separator: "<!--more-->"

categories:

     - 学习笔记
---


<!--more-->

加<!--more-->

2.title为在导航中显示的导航文本，permalink路径的设置需要与文章对应





