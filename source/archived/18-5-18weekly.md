---
title: 首页进度
date: 2018-5-20 23:30:33
tags: weekly
---

#### 本周主要任务

万科首页完成进度如下：
- 5.14 对接周边跟团引擎,优化页面逻辑

- 5.15 按照设计稿还原样式
 对接公共拿到token以及对应解密方法
- 5.16 按照设计稿还原样式,接入邮轮dsf tag还未接入
万科不提供bridge 目前标题对应title 

- 5.17 code review 方法整合，删除部分冗余代码，精简部分方法

#### 主要遇到问题

本周在对接公共的access token的时候，因为他们的cookie是写在预发环境下的，所以我本地的token如果过期的话，是需要重新去拿的。如果是直接输入域名然后点击cookies面板再复制的话未免有点麻烦，所以可以通过配置本地hosts来顺利取到cookies。在hosts文件下写入以下规则：
```
127.0.0.1   xxx.t.ly.com
```
xxx为任意你想配置的域名。这样就可以通过域名访问你的本地服务。
还有个就是原来chrome可以自定义UA。。我才知道。具体就是在切换手机模式的时候有个自定义设备里面可以添加。
其实chrome还有很多牛逼的功能，比如页面优化建议，js单行执行的速度等功能。下次用到的时候再拿出来讲吧。

附：[127.0.0.1和localhost和本机IP三者的区别](https://blog.csdn.net/msdnwolaile/article/details/51278867)
#### 下周任务

完成万科所有任务
