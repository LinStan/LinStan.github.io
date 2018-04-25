---
layout: post
cover: 'assets/images/paopao.jpg'
title: 基于GitHub page搭建个人博客无脑指南
date: 2018-4-25 11:19:00
tags: github blog
author: LinStan
---

<p>之前一直挺羡慕别人搭建的美观的个人博客，因此前两天也买了个域名打算开始搭建。我的BLOG使用的是基于github page和Jekyll模板搭建而成的，搭建环境为Win10 64bit，作为博客的第一篇博文，简单记录一下自己的搭建过程。</p>
<hr />
## Github Page配置##
### 1. github项目建立 ###
登陆 [https://github.com/](https://github.com/ "Github")，登陆注册过程不再赘述。<br>
右上角 “+” 号，点击后选 New repository。假定你github 昵称为：LSS<br>
Repository name 填写为 LSS.github.io(将LSS改为你自己的GitHub昵称)，其余不可改动，这是github分配给每个人的唯一个人主页网址。<br>
下方选项如图<br>
![](https://i.imgur.com/MBOsbU3.jpg)
![](assets/images/paopao.jpg)
进入创建好的repository，下拉至Github Pages可以看到 <br>
> Your site is published at http://LSS.github.io/

其实这时你的个人主页已经开启好了，只是你还没有上传html文件。<br>
再下方有一个Custom domain是用来绑定你的自定义域名的，稍后再介绍
### 2.搭建自己的个性github page ###
首先先安装一个github客户端。[https://gitforwindows.org/](https://gitforwindows.org/)<br>
然后clone你建立的那个项目到本地，进入你的项目主页，点击Clone or download ，复制里面的网址<br>
在你想要作为仓库的路径下右键打开Git Bash Here <br>
输入命令：https://github.com/LSS/LSS.github.io.git  （更改其中的LSS为你的github昵称，更改LSS.github.io为你的项目名.github.io）


