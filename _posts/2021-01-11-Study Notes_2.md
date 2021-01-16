---
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

### title为在导航中显示的导航文本，permalink路径的设置需要与文章对应

### 文章命名要正确,格式如下：
2010-01-10-Study Notes_1

2010-01-10-Study Notes_2

2010-01-10-Graphic Design_1

2010-01-10-Graphic Design_2


### posts文件夹前面要加横杆，不然文章显示不出来，如图
_posts


### 为什么修改背景颜色显示不出来？这就要看你修改的skin是什么，就在相对应的sass里修改了。如果你的skin是night，则不能在sea里面修改。如果多ssas的主题与shin不一样，就会导致你更改背景颜色后无法显示,不仅背景这样，字体也是这样更改。

### 关于拾色器：在修改文字或背景颜色的时候，可以利用拾色器表对照将颜色进行修改，这样你就很容易并且快速找到你想要的颜色啦。可在用浏览器搜索，也可以自行下载一个。

### 神奇的Githubdesktop:利用Githubdesktop，你可以将你的仓库与本地链接，而且还可以进行多项修改再推送。在你修改代码时(假设你用Dreamweaver修改代码），你的Dreamweaver、Githubdesktop和本地仓库时同步的，你在Dreamweaver修改，其他地方也会有变化，如果你修改了文件链路Dreamweaver会弹出窗口让你选择是否同步。在Githubdesktop上，你只要push就可以与远程仓库同步啦!是不是很神奇。之前有的同学在gitee上改代码，一条一条地修改太麻烦啦！








