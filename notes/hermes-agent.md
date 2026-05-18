---
layout: default
title: Hermes Agent 使用指南
date: 2026-05-18
description: Hermes Agent 是一个强大的 AI 助手，可以在终端、即时通讯平台和 IDE 中运行
nav_order: 1
---

# Hermes Agent 使用指南

Hermes Agent 是一个强大的 AI 助手，可以在终端、即时通讯平台和 IDE 中运行。

## 基本使用

### 安装

```bash
curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash
```

### 常用命令

```bash
# 启动交互式聊天
hermes

# 单次查询
hermes chat -q "你的问题"

# 更新
hermes update

# 配置模型
hermes model

# 查看技能
hermes skills list
```

## 技能系统

Hermes 通过技能来学习新能力，比如：

- **obsidian**: 管理 Obsidian 笔记
- **notion**: 操作 Notion 数据库
- **github**: 管理 GitHub 仓库

## 技巧

使用 Hermes 可以自动化很多任务：
- 创建和更新 Markdown 文件
- 自动 Git 提交和推送
- 自动生成 Jekyll 站点
