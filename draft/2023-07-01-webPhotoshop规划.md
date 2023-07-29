---
layout: post
title: "webPhotoshop规划"
tags: [webPhotoshop,协同绘图]
excerpt_separator: <!--more-->
---

# 简介
在我的github上公布了一个名为WebPhotoshop的项目，地址：<a href="https://github.com/leanfish2011/WebPhotoshop-Simple" target="_blank">WebPhotoshop-Simple</a>。这是我十年前开发的，是一个基于HTML5的在线绘图及图形图像处理软件，简单版实现的功能包括：图形绘制、图像处理、图像操作。高级版还可以实现多人协作操作图像、实时交流、图片搜索，同时实现了实时的多人协作处理图形图像功能。

# 设计
## 更名
1. 为了与简单版区分，更名为iPhotoshop

## 代码组织   
1. 前后端放在一个工程中

## 功能
1. 前端功能完善
   部分功能没有实现，继续开发完成。
2. 前端代码拆分
   前端代码耦合度太大，需要进行拆分。可以将前端页面拆分成单个页面，再使用include组合到一起
3. 后端基于netty实现
   使用netty框架实现后端
4. docker一键部署

# 开发计划

# 结束