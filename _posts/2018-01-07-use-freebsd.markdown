---
layout: post
title:  "使用freebsd"
date:   2018-01-07 22:22:18 +0800
categories: jekyll update
---

我选择用freebsd作为服务器。
首先安装python

```
pkg install python
```
然后要安装pip，但是pip要用一个脚本来安装，如何获得脚本？需要curl：
```
pkg install curl
```

安装完curl，下载脚本。
```
curl -0 https://bootstrap.pypa.io/get-pip.py > install-pip.py
```
运行脚本
```
python install-pip.py
```
pip安装成功后，安装Flask。
```
pip install Flask
```
这个时候，要安装git
```
pkg install git
```
然后克隆一个简单的Flask项目。
```
git clone http://www.github.com/gpiopi/zhudoupy
```

```
cd zhudoupy && python main.py
```
然后，访问：
```
localhost:5000
```
