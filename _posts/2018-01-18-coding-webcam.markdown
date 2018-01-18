---
layout: post
title:  "用coding.net的git服务进行硬件控制"
date:   2018-01-18 22:22:18 +0800
categories: jekyll update
---

我们使用coding的git服务来控制内网的硬件设备。

以智能摄像头为例。当然，这个摄像头是罗技摄像头+nanopi制作而成的。

首先，我们在coding上面建立一个私有项目。（github是收费的）


我们需要建立ssh-key。

```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

然后就可以愉快地克隆了

```
git clone git@git.coding.net:GPIOPI/cmd_status.git
```

如果出现错误
```
chmod 700 .ssh/*

```

```
lsusb
ls -l /dev/video0
```

安装fswebcam
```
sudo apt install fswebcam
```



```
sudo apt-get install motion
sudo nano /etc/default/motion
start_motion_daemon=yes
nano /etc/motion/motion.conf
```




daemon off -> daemon on

stream_localhost on -> stream_localhost off
```
sudo service motion start  
sudo motion
```
