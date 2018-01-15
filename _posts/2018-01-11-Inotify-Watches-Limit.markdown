---
layout: post
title:  "Inotify Watches Limit"
date:   2018-01-11 22:22:18 +0800
categories: jekyll update
---

1. Add the following line to either /etc/sysctl.conf file or /etc/sysctl.d/sysctl.conf
/etc/sysctl.d/ directory:
```
```
fs.inotify.max_user_watches = 524288
```

2. Then run this command to apply the change:
```
sudo sysctl -p --system
```
And don't forget to restart your IDE.
