---
layout: default
title: Docker 快速入门
date: 2026-05-18
description: Docker 容器技术基础知识和常用命令
nav_order: 3
---

# Docker 快速入门

## 什么是 Docker

Docker 是一个开源的容器化平台，可以让开发者打包应用及其依赖到一个可移植的容器中。

## 基本概念

- **镜像 (Image)**: 应用的只读模板
- **容器 (Container)**: 镜像的运行实例
- **仓库 (Repository)**: 存放镜像的地方

## 常用命令

### 镜像操作

#### 拉取镜像
```bash
docker pull <image-name>
```

#### 查看本地镜像
```bash
docker images
```

#### 删除镜像
```bash
docker rmi <image-id>
```

### 容器操作

#### 运行容器
```bash
docker run <image-name>
```

#### 查看运行中的容器
```bash
docker ps
```

#### 查看所有容器
```bash
docker ps -a
```

#### 停止容器
```bash
docker stop <container-id>
```

#### 删除容器
```bash
docker rm <container-id>
```

## 实用示例

### 运行 Hello World
```bash
docker run hello-world
```

### 运行 Ubuntu 容器
```bash
docker run -it ubuntu bash
```

### 运行 Nginx
```bash
docker run -d -p 80:80 nginx
```
