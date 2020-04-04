---
layout: post
title: 利用GitHub搭建个人博客
subtitle: 参考柏莹的教程，搭建个人博客
date: 2020-04-03
author: WYB
header-img: img/post-bg-2015.jpg
catalog: true
tags: 
    - Blog
---

# 利用GitHub搭建个人博客
> 参照[柏莹的教程](https://github.com/qiubaiying/qiubaiying.github.io/wiki/%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B)利用github 搭建自己的个人博客，来存放自己的一些学习笔记

## fork repository from qiubaiying
- 登录自己的github账号，fork [qiubaiying.github.io](qiubaiying/giubaiying.github.io) 仓库
![fork qiubaiying.github.io](https://cdn.jsdelivr.net/gh/wangyibin/cloudimg/img/20200404180257.png)

- 修改仓库名
    - 点击settings进入设置
    - 修改仓库名为 `github账号.github.io`, Rename
    > 仓库名一定要以自己的github账号开头，不然会访问不了 

    ![fork rename](https://cdn.jsdelivr.net/gh/wangyibin/cloudimg/img/]_4I4XF_[`7K@611GL7W_3I.png)

- 网站结构
    这个Jekyll 网站的简单结构如下
    ```
    ├── _config.yml
    ├── _drafts
    |   ├── begin-with-the-crazy-ideas.textile
    |   └── on-simplicity-in-technology.markdown
    ├── _includes
    |   ├── footer.html
    |   └── header.html
    ├── _layouts
    |   ├── default.html
    |   └── post.html
    ├── _posts
    |   ├── 2007-10-29-why-every-programmer-should-play-nethack.textile
    |   └── 2009-04-26-barcamp-boston-4-roundup.textile
    ├── _data
    |   └── members.yml
    ├── _site
    ├── img
    └── index.html
    ```
    **重要的文件**
    - `_config.yml` 网站全局配置文件
    - `_posts` 博客文章存放文件夹
    - `img` 图片存放的文件夹


## 修改博客配置
修改博客基础配置文件 `_config.yaml`
### 基础设置
```yaml
# Site settings
title: Bioway Blog
SEOTitle:  Bioway Blog
header-img: img/post-bg-desk.jpg
email: yibinwang96@outlook.com
description: "Every failure is leading towards success."
keyword: "Bioway, Bioway Blog "
url: "http://wangyibin.github.io"          # your host, for absolute URL
baseurl: ""      # for example, '/blog' if your blog hosted on 'host/blog'
github_repo: "https://github.com/wangyibin/wangyibin.github.io.git" # you code repository
```
### 侧边栏
```yaml
# Sidebar settings
sidebar: true                           # whether or not using Sidebar.
sidebar-about-description: "Goals determine what you going to be!"
sidebar-avatar: /img/home_head_icon.jpg      # use absolute URL, seeing it's used in both `/` and `/about/`
```

### 社交账号
```yaml
# SNS settings
RSS: false
# weibo_username:     qiubaiying
#zhihu_username:     qiubaiying
#github_username:    wangyibin
#facebook_username:  baiying.qiu.7
#jianshu_username:   e71990ada2fd
#twitter_username:   qiubaiying
```

### 评论系统
评论系统采用[gittalk](http://qiubaiying.top/2017/12/19/%E4%B8%BA%E5%8D%9A%E5%AE%A2%E6%B7%BB%E5%8A%A0-Gitalk-%E8%AF%84%E8%AE%BA%E6%8F%92%E4%BB%B6/), 需要参照教程，注册配置。
```yaml
# 评论系统
# Disqus（https://disqus.com/）
# disqus_username: qiubaiying

# Gitalk
gitalk:
  enable: true    #是否开启Gitalk评论
  clientID: dcac423844cb4cbadf21                            #生成的clientID
  clientSecret: 21db82aa0a3dd56f4a5503ba3a7bdc6f4c35d85b    #生成的clientSecret
  repo: wangyibin.github.io    #仓库名称
  owner: wangyibin    #github用户名
  admin: wangyibin
  distractionFreeMode: true #是否启用类似FB的阴影遮罩
```
### 网站统计
网站统计，采用[Google Analytic](http://www.google.cn/analytics/), 需要注册提供`ga_track_id`
```
# 统计

# Analytics settings
# Baidu Analytics
ba_track_id: b50bf2b12b5338a1845e33832976fd68

# Google Analytics
ga_track_id: 'UA-162696020-1'            # Format: UA-xxxxxx-xx
ga_domain: auto               # 默认的是 auto, 这里我是自定义了的域名，你如果没有自己的域名，需要改成auto

```
![](https://cdn.jsdelivr.net/gh/wangyibin/cloudimg/img/20200404201953.png)

### 标签
```yaml
# Featured Tags
featured-tags: true                     # 是否使用首页标签
featured-condition-size: 0              # 相同标签数量大于这个数，才会出现在首页
```
### 好友
```yaml
# Friends
friends: [
    {
        title: "CGB",
        href: "http://net.fafu.edu.cn/genome"
    }
]
```


## 修改个人介绍（about）
修改About需修改根目录下的`about.html`


## 发布文章
此博客书写语言为`Markdown`和`yaml`，再配合`git`和`PicGo`等图床软件，使用起来非常方便

### 创建
文章统一存放在`_posts`文件夹中
创建一个新`Markdown`文件`2020-04-03-Hellow_Blog.md`
**格式**

```markdown
---
layout: post
title: Hello Blog
subtitle: Hello Bioway Blog
date: 2020-04-03
author: WYB
header-img: img/post-bg-2015.jpg
catalog: true
tags: 
    - Blog
---

# Hello Blog
## Hello Bioway Blog
```
![](https://cdn.jsdelivr.net/gh/wangyibin/cloudimg/img/20200404204710.png)

![](https://cdn.jsdelivr.net/gh/wangyibin/cloudimg/img/20200404204758.png)



