---
title: nrm使用
date: 2024-04-10 13:49:08
tags: "nrm"
categories: "npm"
---

nrm用于在开发阶段，管理npm的镜像源。

常用命令如下

```shell
# 查看镜像列表
nrm ls
# 查看当前使用镜像
nrm current
# 添加镜像
nrm add <名称> <远程地址或私服地址>
# 删除镜像
nrm del <名称>
# 切换镜像
nrm use <名称>
# 测试镜像网络传输速度
nrm test <名称>
# 查看nrm版本号
nrm <–version | -V>
# 查看nrm的相关信息
nrm <–help | -h>
# 打开镜像的主页
nrm home < 名称> [browser]
# 上传npm包或命令程序
nrm publish [< tarball>|< folder>]
```
