---
layout: default
title: Jekyll 静态网站生成
date: 2026-05-18
description: 使用 Jekyll 快速搭建静态博客和文档网站
nav_order: 4
---

# Jekyll 静态网站生成

## 什么是 Jekyll

Jekyll 是一个简单的、博客感知的静态站点生成器，用 Ruby 编写。

## 安装

```bash
# 安装 Jekyll 和 bundler
gem install jekyll bundler

# 创建新站点
jekyll new my-site
cd my-site

# 启动本地服务器
bundle exec jekyll serve
```

访问 `http://localhost:4000` 查看效果。

## 目录结构

```
my-site/
├── _config.yml      # 配置文件
├── _posts/          # 博客文章
├── _drafts/         # 草稿
├── _layouts/        # 布局模板
├── _includes/       # 可复用组件
├── index.md         # 首页
└── Gemfile          # 依赖管理
```

## Front Matter

每个 Markdown 文件开头需要 Front Matter：

```yaml
---
layout: post
title: 文章标题
date: 2026-05-18
categories: 技术
---
```

## GitHub Pages

GitHub Pages 原生支持 Jekyll：

1. 创建 `username.github.io` 仓库
2. 推送 Jekyll 项目
3. 自动构建和部署
4. 访问 `https://username.github.io`

## 常用主题

- **Just the Docs**: 文档风格
- **Minimal Mistakes**: 博客风格
- **So Simple**: 极简风格
