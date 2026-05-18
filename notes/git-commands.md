---
layout: default
title: Git 常用命令
date: 2026-05-18
description: Git 版本控制系统的常用命令速查
nav_order: 2
---

# Git 常用命令

## 基础命令

### 初始化仓库
```bash
git init
```

### 克隆仓库
```bash
git clone <repository-url>
```

### 查看状态
```bash
git status
```

## 提交更改

### 添加文件
```bash
# 添加所有文件
git add .

# 添加指定文件
git add <file>
```

### 提交
```bash
git commit -m "提交信息"
```

## 分支管理

### 查看分支
```bash
git branch
```

### 创建分支
```bash
git branch <branch-name>
```

### 切换分支
```bash
git checkout <branch-name>
# 或者
git switch <branch-name>
```

### 合并分支
```bash
git merge <branch-name>
```

## 远程仓库

### 添加远程仓库
```bash
git remote add origin <url>
```

### 推送
```bash
git push -u origin main
```

### 拉取
```bash
git pull
```

## 实用技巧

### 撤销上次提交
```bash
git reset --soft HEAD~1
```

### 查看提交历史
```bash
git log --oneline
```
