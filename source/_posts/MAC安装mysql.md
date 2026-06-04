---
title: MAC安装mysql
tags: 科学上网
categories: 技术
abbrlink: 1012cdbb
date: 2024-11-21 14:24:23
---

在mac电脑使用brew安装mysql。

先查找可以安装的mysql版本。

```shell
brew search mysql

> brew search mysql
==> Formulae
automysqlbackup            mysql-client@8.0           mysql@8.0
mysql                      mysql-client@8.4           mysql@8.4
mysql++                    mysql-connector-c++        mysqltuner
mysql-client               mysql-search-replace       qt-mysql
mysql-client@5.7           mysql@5.7

==> Casks
mysql-connector-python     mysqlworkbench             sqlpro-for-mysql
mysql-shell                navicat-for-mysql
```



本来想安装mysql@8.4版本，但是由于我的操作系统是 mac 15.1 版本无法安装。退而求其次安装mysql@8.0版本。



### 安装

```shell
brew install mysql@8.0
```
