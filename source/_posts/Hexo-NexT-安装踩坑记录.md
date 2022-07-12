---
title: Hexo-NexT 安装踩坑记录
mathjax: true
date: 2022-07-12 16:22:10
tags:
- 踩坑记录
categories:
- 技术
- 踩坑记录
---

## Hexo-NexT 安装踩坑记录

### 背景图片设置

在 `.\themes\next\_config.yml` 设置好 `custom_file_path` 的 `style` 属性后，那个路径里面的 `/source/_data/styles.styl` 要建在根目录的 `source` 下而不是 `.\themes\next` 目录下的

