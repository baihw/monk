# monk
![License](https://img.shields.io/hexpm/l/plug.svg)
[![Build Status](https://travis-ci.org/baihw/monk.svg?branch=master)](https://travis-ci.org/baihw/monk)
[![GoDoc](https://godoc.org/github.com/baihw/monk?status.svg)](http://godoc.org/github.com/baihw/monk)

monk 是一个基于Apache License v2.0开源协议的轻量级应用服务器。

## Docker 容器

### 稳定版
```
docker pull baihw/monk
docker run -p 8080:9998 baihw/monk server /work
``` 

### 尝鲜版
```
docker pull baihw/monk:edge
docker run -p 8080:9998 baihw/monk:edge server /work
```
更多Docker部署信息请访问 [这里](https://github.com/baihw/monk/docs/monk-docker-quickstart-guide)

## 下载二进制文件

### macOS
| 操作系统| CPU架构 | 地址|
| ----------| -------- | ------|
|Apple macOS|64-bit Intel|https://github.com/baihw/monk/releases/darwin-amd64/monk |
```sh
chmod 755 monk
./monk server /work
```

### GNU/Linux
| 操作系统| CPU架构 | 地址|
| ----------| -------- | ------|
|GNU/Linux|64-bit Intel|https://github.com/baihw/monk/releases/linux-amd64/monk |
```sh
chmod +x monk
./monk server /work
```

### 微软Windows系统
| 操作系统| CPU架构 | 地址|
| ----------| -------- | ------|
|微软Windows系统|64位|https://github.com/baihw/monk/releases/windows-amd64/monk.exe |
```bat
monk.exe server D:\work
```

## 入门指导

待补充

## 如何参与到Monk项目
请参考 [贡献者指南](https://github.com/baihw/monk/blob/master/CONTRIBUTING.md)。欢迎各位中国程序员加到Monk项目中。
