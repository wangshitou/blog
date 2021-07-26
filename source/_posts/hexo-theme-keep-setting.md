---
title: hexo-theme-keep主题的设置
date: 2021-07-26 18:43:33
tags: [hexo,hexo-theme-keep]
---

```
安装hexo-theme-keep主题
git clone https://github.com/XPoet/hexo-theme-keep themes/keep

修改配置文件主题设置为keep
theme: keep


开启标签功能
theme-keep配置文件开启
tag:
    enable: true
根目录运行命令，生成tags首页文件
hexo n page tags


开启搜索功能
Hexo 之 Local Search
Hexo提供的Local Search,原理是通过hexo-generator-search插件在本地生成一个search.xml文件，搜索的时候从这个文件中根据关键字检索出相应的链接。
安装步骤
安装 hexo-generator-search
在站点的根目录下执行以下命令：
npm install hexo-generator-search --save

安装 hexo-generator-searchdb
在站点的根目录下执行以下命令：
npm install hexo-generator-searchdb --save

```
