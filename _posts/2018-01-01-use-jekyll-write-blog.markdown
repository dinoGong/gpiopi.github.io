---
layout: post
title:  "使用Jekyll来写博客"
date:   2018-01-01 22:22:18 +0800
categories: jekyll update
---

以前我也是一个程序员，但自从做了产品，则发现，重复写轮子的精神虽然可佳，但是搭积木的方法更为可取。不一定所有的东西都要自己重新造一个出来，但可以选择更适合该项目的现成部件。

总之，人生苦短，何必用重复写轮子来折磨自己？

所以，这次我也不用自己写的博客系统写博客了，干脆直接用jekyll，这样可以节省时间去思考更值得思考的问题。

jekyll基于ruby，所以要先安装ruby。好在kali（base on debian）系统自带。于是，我们直接用gem安装即可：
```
#gem install jekyll bundle
#jekyll new blog
#cd myblog
#bundle exec jekyll serve
```
