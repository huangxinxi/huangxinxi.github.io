---
layout: post
title:  "MySQL Notifier开机提醒High Severity Error缺少根元素"
date:   2020-05-11
categories: Mysql
tags: Mysql
---

今天开机Mysql Notifier突然提示“High Severity Error缺少根元素”<br>
去网上找了很多篇博客 <br>
发现有说去C盘特定路径下删除settings.config文件然后重启的，但是我没有找到这个路径<br>（C:\Users\Administrator\AppData\Roaming\Oracle\MySQL Notifier）<br>
然后在另外一篇博客中找到了一个通用路径，只要在地址栏中输入%AppData%\Oracle\MySQL Notifier\ 即可找到这个settings.config文件进行删除<br>
一些博客上说重启以后会提醒一个重新生成settings.config的提示，但是我发现有一些人留言说是重启没提示，我也遇到了这样的问题<br>
最后我的解决办法是卸载掉了Mysql Notifier，不影响Mysql的正常使用<br>

参考资料：https://blog.csdn.net/y694721975/article/details/52997623?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-4.nonecase&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-4.nonecase