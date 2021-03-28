---
title: "First"
date: 2021-03-11T22:50:12+09:00
draft: flase
author: cho
---

- 目标: 建立测试文件，并且在主页上显示测试文件的标题，添加文件的连接

1. 网页的格式由一个单页格式控制文件(single.html)文件和一个列表文件控制(list.html)
2. 函数，变量等只能用在html文件中
3. 主页的列表文件需要一个特殊的文件控制(_index.md)，位于根文件下,如果要显示index。md中的内容需要在list.html中添加使用变量
4. 在list中为文章的标题添加连接。


- 问题

1. 主页文件只显示文件夹路径并没有显示文件夹之下的文章标题
2. 主文件夹之下只有一个post的文件夹，并没有文件

- 层关系
  - baseof.html 
    - list.html
      - index.html
    - single.html
  - section