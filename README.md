![MiHo](http://oerolc7og.bkt.clouddn.com/images/miho/theme/github.jpg)
hexo-theme-miho
================

MiHo is a single and responsive design theme for [Hexo](//hexo.io).
MiHo requires Hexo 3.0 and above, Compatible with mobile browsing; Theme DEMO:[MinHow's Blog](http://blog.minhow.com/).
中文文档请[查看](http://blog.minhow.com/2017/08/01/blog/installation-configuration/).

## Summary
* [General](#general)
* [Features](#features)
* [Installation](#installation)
* [Configuration](#configuration)
* [Contributing](#contributing)
* [License](#license)

## General
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg?style=flat-square)](#)
[![Author](https://img.shields.io/badge/author-MinHow-blue.svg?style=flat-square)](https://minhow.com)

[![Hexo](https://img.shields.io/badge/hexo-3.0+-green.svg?style=flat-square)](https://hexo.io)
[![node.js](https://img.shields.io/badge/node.js-6.0+-green.svg?style=flat-square)](https://nodejs.org/)

## Features
* Responsive
* Concise
* Tags Support & Categories Support
* Googe analytics & Baidu analytics & Cnzz analytics
* Disqus comments & Changyan comments
* Stylus CSS preprocessor
* Local Site Search
* Pagination
* ejs HTML templates

## Installation

### Installation Theme
``` bash
$ git clone https://github.com/WongMinHo/hexo-theme-miho.git themes/miho
```

### Update
``` bash
cd themes/miho
git pull
```

### Dependency installation
#### Json-content
Generate site articles static data for in-site search; detailed configuration please check [hexo-generator-json-content](https://github.com/alexbruno/hexo-generator-json-content).
``` bash
npm install hexo-generator-json-content --save
```

### Theme Config
Change theme field in Hexo root's `_config.yml` file.
``` bash
theme: miho
```

## Configuration
Modify settings in `themes/miho/_config.yml`，Please use it as needed.

```
# hexo-theme-miho
# https://github.com/wongminho/hexo-theme-miho

# Favicon of your site | 网站icon
favicon: /favicon.ico

# Header

# Keywords of your site | 网站关键字
keywords: MinHow,MinHow's Blog
# Head headline | 头部标题
header_title: MinHow's Blog
# Head description | 头部描述
header_description: 一个专注 WEB 开发的技术博客
# Link to your logo | logo地址
logo: images/logo.png
# Link to your banner_img | 首页banner图地址
banner_img: images/banner.jpg
# Head navigation, use to display social information | 头部导航，用来展示社交信息
header_nav:
  home: "//minhow.com"
  github: "//github.com/wongminho"
  weibo: "//weibo.com/WongMinHo"
  twitter: "//twitter.com/huangminhow"
  #qq: "#"
  #weixin: "#"
  #snapchat: "#"
  #telegram: "#"
  #mail: "#"
  #facebook: "#"
  #google: "#"
  #linkedin: "#"

# Content

# Excerpt length | 摘录长度
excerpt_length: 190
# Excerpt link | 摘录链接
excerpt_link: more>>
# New window open link | 新窗口打开文章
open_new_link: false
# Article default cover picture，size：350*150 | 文章默认封面图，尺寸：350*150
cover_picture: images/banner.jpg
# Open background particles | 开启背景粒子
open_bg_particle: true
# Open animation in homepage and head | 开启主页及头部动画
open_animation: true

# Style customization | 样式定制
style:
  # Main color tone | 主色调
  main_color: '#0cc'

# Comments | 评论

# 畅言
changyan_appid: false
changyan_conf: false
# disqus
disqus: false

# Analytics | 分析
# 站长分析，输入站点id
cnzz_analytics: false
# 百度分析，输入key值
baidu_analytics: false
# google analytics | google分析
google_analytics: false

# Footer

# Access statistics | “不蒜子”访问量统计
access_counter:
  on: true
  site_uv: 总访客数：
  site_pv: 总访问量：

# Copyright Information | 版权信息
copyright: 2017 MinHow
```

#### Article cover picture
Article default cover picture，size：350*150, When the article configuration does not have cover_picture display.
``` bash
cover_picture: images/banner.jpg
```

#### Background particles
Whether to open background particles.
``` bash
open_bg_particle: true
```

#### Homepage and head animation
Whether to open homepage and head animation.
``` bash
open_animation: true
```

#### Analytics
Google analytics, Baidu analytics and cnzz analytics are supported.
``` bash
# 站长分析，输入站点id
cnzz_analytics: false
# 百度分析，输入key值
baidu_analytics: false
# google analytics | google分析
google_analytics: false
```

#### Comments
This theme support both Disqus and Changyan as the third party discussion system.
``` bash
# 畅言
changyan_appid: false
changyan_conf: false
# disqus
disqus: false
```

### Article configuration example
``` bash
---
title: Hello World
date: 2017-06-18
categories: First
tags:
    - First
    - Second
---
MinHow-This is a summary
<!-- more -->
cover_picture: /images/banner.jpg
---
```

## Contributing
All kinds of contributions (enhancements, new features, documentation & code improvements, issues & bugs reporting) are welcome.

## License
Open sourced under the GPL v3.0 license.


