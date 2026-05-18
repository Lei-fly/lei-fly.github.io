---
layout: default
title: 知识库
parent: 知识库
nav_order: 1
has_children: true
---

# 📚 我的知识库

欢迎来到我的知识库！这是一个由 Hermes 管理的技术笔记与随笔网站。

## 🎯 特点

- 📚 基于 **Just the Docs** 主题，清晰的文档风格
- 🌓 支持深色/浅色模式切换（右上角切换）
- 🔍 内置搜索功能
- 💬 支持 giscus 评论（GitHub Discussions）
- 📱 响应式设计，支持移动端
- ⚡ GitHub Pages 自动构建

## 📂 内容分类

{% for node in site.pages %}
{% if node.dir == "/notes/" and node.name != "index.md" %}

### [{{ node.title }}]({{ node.url }})
{{ node.description }}
{% endif %}
{% endfor %}

## 🔧 使用说明

### 浏览笔记
使用左侧导航栏，点击分类浏览具体笔记。

### 搜索内容
点击顶部搜索图标（🔍），输入关键词查找相关笔记。

### 切换主题
点击右上角主题按钮，切换深色/浅色模式。

### 评论交流
在每篇文章底部可以发表评论（需要 GitHub 账号）。

---

*本站由 [Hermes Agent](https://github.com/NousResearch/hermes-agent) 自动维护*
