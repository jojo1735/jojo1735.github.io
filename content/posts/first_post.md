---
title: "First_post"
date: 2021-05-22T18:50:03+08:00
tag: test
draft: false
toc: false
isCJKLanguage: true
images:
tags: 
  - 文章
---

![image.png](https://cdn.nlark.com/yuque/0/2021/png/453178/1621363095058-247c675f-274d-4efb-acc1-6631f178149f.png#align=left&display=inline&height=2088&margin=%5Bobject%20Object%5D&name=image.png&originHeight=2088&originWidth=4000&size=831911&status=done&style=stroke&width=4000)

# 1.计算机网络如何运行

互联网采取client-server结构，client就是你的浏览器，server存储所有的文件。
![image.png](https://cdn.nlark.com/yuque/0/2021/png/453178/1621368278959-0c4db1ec-9f3e-4e35-bf48-846ad15847be.png#align=left&display=inline&height=175&margin=%5Bobject%20Object%5D&name=image.png&originHeight=350&originWidth=1302&size=53903&status=done&style=none&width=651)

- http/https

超文本传输协议，网络传输数据。
安全的http，需要来自第三方供应商的安全证书来保护连接并验证该站点是否安全。此安全证书称为**_SSL（安全套接字层）_**
**_![image.png](https://cdn.nlark.com/yuque/0/2021/png/453178/1621368359344-57fa5c33-945a-4334-8dd1-579aaf04ab95.png#align=left&display=inline&height=445&margin=%5Bobject%20Object%5D&name=image.png&originHeight=890&originWidth=1572&size=70181&status=done&style=none&width=786)_**

- dns
- hosting
- 浏览器
- 域名

# 2.你应该知道的web开发者基本工具

## 2.1终端

在基于macOS和Linux的计算机上，自带bash终端，它是开发人员中最受欢迎的终端，因为它提供了最好的工具包，而没有兼容性问题；
Windows操作系统，通过WSL2（适用于Windows的Linux子系统）在UNIX的工作空间中使用WSL2

- bash
- zsh
- git bash

## 2.2设计

- figma（推荐）
- adobe xd

## 2.3浏览器

- chrome（dev tools）

## 2.4文本编辑器

在熟练使用其中一种编辑器功能之前，不使用其它的。

- vscode（推荐）
- atom
- sublime text

# 3.html

- 最佳实践
- seo
- 语义 html
- 表单与验证

# 4.css

## 4.1css基础

- css grid

布局，包括位置，尺寸，对其。

- flexbox

css3中的布局模式。

- 自定义属性

css变量，自定义实体。

## 4.2现代css

- css模块
- 样式化组件（styled components）

高级

## 4.3css框架

- Tailwind css
- bootstrap

## 4.4响应式设计

不同屏幕尺寸的适配

- viewport

视口。移动设备出现后的概念。网页不再是固定大小。

- rem units

根据W3C规范，rems单位是根元素上font-size的计算值，在根元素的font-size属性中指定时，rem单位是指属性的初始值。

- css媒体查询（media queries）

在浏览器和设备环境与您可以指定的规则匹配时才应用CSS的方法

## 4.5css 预处理

- sass（推荐）
- postcss（简单易扩展）

## 4.6动画

- 普通动画（plain css）
- gsap

适合初学者。应用于web程序和游戏。

- anime.js



**选择你的栈**

# 5.前端

## 5.1学习JavaScript

- 基本语法
- fetch api
- json
- es6/es7
- typescript

## 5.2JavaScript栈

### 5.2.1推荐工具

- git 
- github
- npm script
- prettier
- eslint
- axios
- vscode插件
- 浏览器开发者工具

### 5.2.2包管理

- npm*
- yarm

### 5.2.3模块打包

- webpack
- parcel
- rollup



### 5.2.4前端框架

### 5.2.5pwa

## 5.3前端框架

### 5.3.1react

灵活

### 5.3.2vue

简单，灵活

### 5.3.3angular

### 5.3.4状态管理

- react：redux，context api
- **vue：vuex**
- **angular：services**

### 5.3.5ssr-服务端渲染

- **vue：nuxt.js **[https://nuxtjs.org/](https://nuxtjs.org/)
- **react：next.js**

### 5.3.6静态网站生成器

- **vue：gridsome，nuxt.js **[https://nuxtjs.org/](https://nuxtjs.org/)
- **react：gatsby，next.js**

# 6.后端

## 6.1后端框架

- node.js(javascript)
- deno(js)
- flask(pthon)

wsgi框架

- django(python)

全栈web框架

## 6.2数据库

### 6.2.1关系型

- mysql
- postgresql

### 6.2.2nosql/云数据库

- mongodb（推荐）
- aws（易于扩展）
- firebase（小型项目绝佳选择）

## 6.3APIs

### 6.3.1授权authentication

- oauth
- jwt（**JavaScript Web令牌**）

### 6.3.2providers

- auth0
- firebase



## 6.4CMS(内容管理系统)

### 6.4.1传统

- wordpress
- drupal

### 6.4.2无头

- netlify cms
- strapl
- prismic
- storyblok



## 6.5部署

### 6.5.1需要学习的概念

- 负载平衡（load balancing）
- github actions
- ssh
- 监控monitoring
- 安全security
- ssl证书

### 6.5.2无服务器（serveless/FaaS）

- aws lambda
- netlify

### 6.5.3web服务器

- apache
- nginx

### 6.5.4hosting（网站托管，主机空间，虚拟主机服务）

- 静态：netlify，github pages
- heroku
- aws
- azure
- linode

### 6.5.5测试

- 单元测试
- 集成测试
- 功能测试

### 6.5.6虚拟化

- docker
- Kubernetes



