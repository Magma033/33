---
layout: page
title: 搭建Jekyll网站，你准备好了吗？
excerpt_separator: "<!--more-->"
categories:
     - 学习笔记
---

#### 如何搭建jekyll网站？

<!--more-->

### 第一步 网站托管
我们知道，一个网站要能够在任何地方都能够被访问，那么需要部署到服务器上。其实github就提供了这样的功能，只要按照github格式要求，新建一个仓库，把你的网站代码上传到里面，那么就可以在任何时候任何地方都能够访问了，那么如何搭建这个代码托管仓库呢？

1.首先你要到GitHub上注册一个账号。

2.点击New repository创建一个新的仓库，并给它命名。

3.把改仓库拉取到本地，可以使用Githubdesktop把仓库克隆进本地， 然后在里面新建一个index.html的文件,在里面输入任意内容，然后再把代码推送到git上，然后再访问改链接，可以发现index.html里面的内容被访问到了。到这里，一个免费且无限流量的github代码托管仓库就创建完成了。

### jekyll的安装
jekyll相当于一个编译工具，安装好jekyll后，你可以通过jekyll创建一个网站模板，创建好之后，我们就可以通过链接访问创建的网站了，我们可以实时修改刚刚创建的模板里面的内容，并可以实时通过本地url预览改动后的效果。

安装jekyll：

首先点击下载安装Ruby installer;
点击下载RubyGems,下载完成后解压至你想放的位置
在命令行执行gem install jekyll；
安装完成，我们可以用jekyll命令创建一个博客模板,打开命令行执行

### jekyll的结构目录

- _posts 博客内容
- _pages 其他需要生成的网页，如About页
- _layouts 网页排版模板
- _includes 被模板包含的HTML片段，可在_
- config.yml中修改位置
- assets 辅助资源 css布局 js脚本 图片等
- _data 动态数据
- _sites 最终生成的静态网页
- _config.yml 网站的一些配置信息
- index.html 网站的入口
