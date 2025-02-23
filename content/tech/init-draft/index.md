+++
date = '2025-02-23T23:01:11+08:00'
draft = false
title = 'Init Draft'
+++

# 设置好之后，本地可以，github pages不更新
<!--more-->
本地终端执行 hugo server -D 的时候，本地草稿态在浏览器内访问正常。
但是upload到github上就是不行。
github actions应该没问题。
所以上网查了下，尝试了一堆办法，一开始使用 hugo进行编译，没用。
后来把每一个文章中的初始化中的设置draft 改为了 false后就可行了。
