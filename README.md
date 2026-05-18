# lei-fly.github.io

我的知识库网站，由 [Hermes Agent](https://github.com/NousResearch/hermes-agent) 自动维护。

## 🌐 访问地址

https://lei-fly.github.io

## 📁 结构

```
lei-fly.github.io/
├── _config.yml          # Jekyll 配置
├── index.md             # 首页
├── Gemfile              # Ruby 依赖
└── notes/               # 笔记目录
    ├── 技术/
    ├── 笔记/
    └── 随笔/
```

## 🚀 技术栈

- **Jekyll** - 静态网站生成器
- **Just the Docs** - 文档主题
- **GitHub Pages** - 托管
- **giscus** - 评论系统

## 📝 添加笔记

笔记由 Hermes Agent 自动管理，直接告诉它：

```
"帮我创建一个关于 [主题] 的笔记"
```

Hermes 会自动：
1. 创建/更新 Markdown 文件
2. 提交到 Git
3. 推送到 GitHub
4. 自动更新网站

## 🔧 本地开发

```bash
# 安装依赖
bundle install

# 本地运行
bundle exec jekyll serve

# 访问
http://localhost:4000
```

## 📄 许可

© 2026 Lei-fly. All rights reserved.
