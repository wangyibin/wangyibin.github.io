---
layout: post
title: 利用PicGo搭建github图床
subtitle: 利用PicGo软件搭建存储地址在github的图床
date: 2020-04-04
author: WYB
header-img: img/post-bg-2015.jpg
catalog: true
tags: 
    - Blog
    - github
    - windows
---

# 利用PicGo搭建github图床
> 搭建在线图床平台，提升Markdown的写作效率。

## Github 仓库配置
### 创建新github仓库
创建一个新的github仓库，用来存放图片
![](https://cdn.jsdelivr.net/gh/wangyibin/wangyibin.github.io/img/cloudimg/20200404172055.png)
![](https://cdn.jsdelivr.net/gh/wangyibin/wangyibin.github.io/img/cloudimg/20200404172240.png)
### 创建token，并复制token
提供github token 给PicGo
打开 个人 -> `settings` -> `Devoloper settings` -> `Personal access tokens` -> `Generate new token` -> `Copy`
![Developers settings](https://cdn.jsdelivr.net/gh/wangyibin/wangyibin.github.io/img/cloudimg/20200404171427.png)
![generate token](https://cdn.jsdelivr.net/gh/wangyibin/wangyibin.github.io/img/cloudimg/20200404171259.png)

## PicGo客户端配置
### 下载和安装
PicGo是一款开源的图床工具，具有多个对象存储平台，使用非常方便。

下载地址：
- [github](https://github.com/Molunerfinn/PicGo)

下载完后安装
![picgo 主界面](https://cdn.jsdelivr.net/gh/wangyibin/wangyibin.github.io/img/cloudimg/20200404171854.png)

### 配置
配置PicGo Github图床设置
![picgo github setting](https://cdn.jsdelivr.net/gh/wangyibin/cloudimg/img/20200404173213.png)

网址可以设置为cdn国内加速
> https://cdn.jsdelivr.net/gh/wangyibin/cloudimg

### 快捷键设置
PicGo 可以上传剪贴板的图片文件，配合截图软件使用（例如snipaste）可以提高效率。我设置为`F2`。
![](https://cdn.jsdelivr.net/gh/wangyibin/cloudimg/img/20200404173534.png)
![](https://cdn.jsdelivr.net/gh/wangyibin/cloudimg/img/20200404173625.png)


## 总结
利用图床工具可以提高Markdown的书写效率，PicGo具有多个对象存储借口，本人使用github方便，并**免费**，总之PicGo+github让我对Markdown的写作效率提升了一大截。