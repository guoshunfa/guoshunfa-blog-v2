---
title: Nexus 介绍
tags:
    - shell
    - expect
categories:
    - 技术
date: 2023-06-28 11:31:38
thumbnail:
---
> 注意：Nexus 3.X要求JDK的版本在1.8以上

## 1. 安装、运行

### 1.1. 下载对应安装包

前往官方[下载地址](https://www.sonatype.com/oss-thank-you-mac-tgz)

mac系统提供[百度网盘](https://pan.baidu.com/s/1To7wwl29xQKmxSEyXckX1w)，提取码：5fsw

### 1.2. 运行Nexus

进入对应的bin目录下启动nexus

```shell
./nexus start
```

出现`Starting Nexus OSS... Started Nexus OSS.`，即启动成功。

### 1.3. 访问地址

- 3.x默认是127.0.0.1:8081，默认的登陆账户密码为admin/admin123。
- 2.x默认是127.0.0.1:8081/nexus，默认的登陆账户密码为admin/admin123。

![](https://file.pandacode.cn/blog/20211224163336.png)
