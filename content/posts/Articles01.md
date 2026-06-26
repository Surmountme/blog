---
title: Hugo 简介
date: 2026-06-26T16:45:06+08:00
lastmod: 2026-06-26T16:45:06+08:00
author: Surmountme
# avatar: /img/author.jpg
# authorlink: https://author.site
# cover: /img/cover.jpg
# covercaption: a description of the cover image
# images:
#   - /img/cover.jpg
categories:
  - 技术
tags:
  - 测试
  - 博客
# nolastmod: true
# math: true
draft: false
---


# Hugo

&emsp; &emsp; Hugo 是一个使用 Go 编写的开源静态网站生成器（Static Site Generator，SSG）。它以极快的构建速度、灵活的模板系统以及丰富的内容管理能力而闻名，被广泛用于博客、技术文档、企业官网和产品网站等场景。

# 核心特点

&emsp; &emsp; Hugo 的设计目标是快速、简单且可扩展。它无需数据库或运行时服务器，在构建时直接将 Markdown 等内容渲染为静态 HTML，因此生成的网站安全性高、部署简单，并且可以轻松托管到 CDN 或静态托管平台。官方介绍中强调，大型站点通常也能在数秒甚至更短时间内完成构建。主要能力包括：

- 极速构建：Go 实现，适合包含成千上万页面的大型网站。
- Markdown 内容创作：以 Markdown 为主要内容格式，也支持其他输入格式。
- Go Template 模板系统：可高度定制页面布局与输出。
- 多语言支持：内建国际化（i18n）和本地化能力。
- 资源处理（Hugo Pipes）：支持图片处理、JavaScript 打包、Sass 编译、CSS/JS 压缩等。
- 多种输出格式：除 HTML 外，还能生成 RSS、JSON、CSV 等内容。

# 常见应用场景

&emsp; &emsp; Hugo 被广泛用于各种静态内容网站，包括：

- 技术文档
- 开发者门户
- 博客
- 企业官网
- 产品落地页（Landing Page）
- 新闻网站
- 活动网站
- 个人作品集与简历

&emsp; &emsp; 由于生成的是静态文件，这些网站通常具有较好的访问性能，并且部署到 GitHub Pages、Netlify、Cloudflare Pages 等静态托管平台非常方便

