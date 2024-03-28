---
title: mac安装nginx
date: 2024-03-22 20:34:11
tags: "Nginx"
categories: "技术"

---

nginx

```shell
# 安装 nginx
brew install nginx
# 卸载 nginx
brew uninstall nginx
brew uninstall nginx@版本号
# 查看 nginx 安装信息
brew info nginx
# 启动、停止、重启nginx(推荐)
brew services start nginx
brew services stop nginx
brew services restart nginx
# nginx原生常用命令启动、停止、重新加载配置文件(不推荐)
nginx #启动nginx
nginx -s reload #重新加载配置文件 ，热加载配置文件
nginx -s quit #:推荐 待nginx进程处理任务完毕进行停止
nginx -s stop #:先查出nginx进程id再使用kill命令强制杀掉进程。

# 查询 nginx 进程
ps aux|grep nginx
ps -ef|grep nginx


# 配置 nginx
```
