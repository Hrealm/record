---
lang: zh-CN
title: 指南
description: 页面的描述
---

# 页面
VuePress 是以 Markdown 为中心的。你项目中的每一个 Markdown 文件都是一个单独的页面。

## 路由
默认情况下，页面的路由路径是根据你的 Markdown 文件的相对路径决定的。

假设这是你的 Markdown 文件所处的目录结构：
```
└─ docs
  ├─ guide
  │  ├─ getting-started.md
  │  └─ README.md
  ├─ contributing.md
  └─ README.md
```

## Frontmatter
Markdown 文件可以包含一个 YAML Frontmatter 。Frontmatter 必须在 Markdown 文件的顶部，并且被包裹在一对三短划线中间。下面是一个基本的示例：

## 内容
页面的主要内容是使用 Markdown 书写的。VuePress 首先会将 Markdown 转换为 HTML ，然后将 HTML 作为 Vue 单文件组件的 `<template> `。

借助 markdown-it 和 Vue 模板语法的能力，基础的 Markdown 可以得到很多的扩展功能。接下来，前往 Markdown 章节来了解 VuePress 中 Markdown 的扩展功能。

### wer

45654