---
layout: post
title:  "烧录一个U盘启动的linux系统"
date:   2018-01-03 22:22:18 +0800
categories: jekyll update
---
```
fdisk -l
```
```
dd bs=4M if=/path/to/antergos-x86_64.iso of=/dev/sdX status=progress && sync
```

GUI's

```
https://etcher.io/
```

ISO:

DragonFly BSD
```
wget http://mirror-master.dragonflybsd.org/iso-images/dfly-x86_64-5.0.2_REL.iso.bz2
```

```
wget http://mirror-master.dragonflybsd.org/iso-images/dfly-x86_64-5.0.2_REL.iso
```

linuxmint
```
wget https://mirrors.tuna.tsinghua.edu.cn/linuxmint-cd/stable/18.3/linuxmint-18.3-kde-64bit.iso
```

q4os
```
wget https://sourceforge.net/settings/mirror_choices?projectname=q4os&filename=stable/q4os-2.4-x64.r3.iso
```

trueOS
```
wget http://download.trueos.org/master/amd64/TrueOS-Desktop-17.12-x64-DVD.iso
```


base debian
crunchbang++
```
https://crunchbangplusplus.org/download/
```

```
https://sourceforge.net/projects/sparkylinux/files/xfce/
```

smail linux
```
http://mirror.slitaz.org/iso/rolling/slitaz-rolling.iso
```
