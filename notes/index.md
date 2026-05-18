---
layout: default
title: 知识库
nav_order: 1
has_children: false
---

# 📚 我的知识库

这里记录着我的学习笔记、技术总结和思考随笔。

---

## 📝 最新笔记

{% assign sorted_pages = site.pages | sort: 'date' | reverse %}
{% for page in sorted_pages %}
{% if page.dir == "/notes/" and page.name != "index.md" and page.title %}

### [{{ page.title }}]({{ page.url }})
{{ page.date | date: "%Y-%m-%d" }} - {{ page.description }}
{% endif %}
{% endfor %}

---

*使用左侧导航栏浏览所有笔记*
