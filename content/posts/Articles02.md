---
title: 'Articles02'
date: '2026-06-26T17:13:09+08:00'
author: Surmountme



categories:
  - 闲谈
tags:
  - 测试
  - 博客
draft: false
---

# Astro

&emsp; &emsp; Astro 是一个基于 JavaScript 的开源 Web 框架，以构建内容驱动型网站为核心目标，同时也是目前最受欢迎的静态站点生成器（SSG）之一。它因默认输出轻量 HTML、尽量减少客户端 JavaScript，以及兼顾静态生成与服务器渲染能力而受到博客、文档、营销网站和作品集开发者的广泛采用。

# 核心特性

&emsp; &emsp; Astro 的设计理念围绕性能和内容展开，其最具代表性的特点包括：

- 默认零 JavaScript（Zero JS by default）：页面仅发送必要的 HTML，除非开发者明确启用交互组件，从而减少浏览器负担。
- Islands Architecture（岛屿架构）：只有需要交互的部分才会在客户端水合（hydrate），静态内容保持纯 HTML。
- 内容优先：非常适合博客、文档、新闻站点、营销页面和电子商务展示页。
- 多框架支持：可以在同一项目中混合使用 React、Vue、Svelte、Solid、Preact、Lit 等组件，而无需锁定某一种前端框架。

# 开发体验

&emsp; &emsp; Astro 使用 .astro 文件作为组件格式，其语法接近 HTML，并允许在组件顶部编写服务器端 JavaScript。它还提供：

- 基于 Markdown 和 MDX 的内容管理
- 内置路由
- 图片优化
- TypeScript 支持
- 丰富的集成（如 Tailwind CSS、React、Vue、Svelte 等）
- 静态站点生成（SSG）和服务器端渲染（SSR）两种输出模式

# 适用场景

&emsp; &emsp; Astro 最适合以下类型的网站

- 博客
- 技术文档
- 产品官网
- 企业展示网站
- 个人作品集
- 内容型电子商务页面

&emsp; &emsp; 对于需要大量实时交互、复杂客户端状态管理或类似社交平台、在线办公应用的 Web 应用，它通常不是首选，此类项目更常使用 React、Next.js 等以应用开发为中心的框架。