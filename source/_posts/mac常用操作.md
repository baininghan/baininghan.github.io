---
title: mac常用操作
date: 2024-03-05 16:34:11
tags: "记录"
categories: "技术"
---

### mac电脑安装软件，提示已损坏

```shell
sudo spctl  --master-disable
sudo xattr -r -d com.apple.quarantine /Applications/XXXX.app
```

### Myql启动命令

```shell
mysql.server start
```

### Redis

```shell
# 启动服务端
redis-server
# 关闭服务端
edis-cli SHUTDOWN
# 启动客户端，按照默认配置连接redis（127.0.0.1:6379）
redis-cli
# 启动客户端，指定地址和端口号
edis-cli -h 127.0.0.1 -p 6379
# redis 设置临时密码
config set requirepass 密码
# redis 获取临时密码
config get requirepass
```

### npm相关

```shell
# 安装 pnpm，提升依赖的安装速度
npm config set registry https://registry.npmjs.org
npm install -g pnpm
# 安装依赖
pnpm install

# 启动服务
npm run dev
```

### svn

```shell
# 下载代码库
svn checkout [repository URL] [local directory]
# 提交代码
svn commit -m "commit message"
# 更新代码
svn update
# 查看文件更改
svn status
# 撤销更改
svn revert [file name]
```

### nacos 启动

```shell
sh startup.sh -m standalone
# 浏览器访问
```
