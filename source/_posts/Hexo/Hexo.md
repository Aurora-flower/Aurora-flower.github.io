---
layout: post
title: 初见 hexo
date: 2024-06-30 04:40:12
categories: [初见 hexo]
tags: [Extend]
---

## 前言

hexo 是一个快速、简洁且高效的博客框架。

---

### 创建新文章

```shell
hexo new [title]
```

更多信息: [Writing](https://hexo.io/docs/writing.html)

### 使用草图

草图是未发布的文章，可以通过以下命令查看和发布草图：

```shell
hexo draft "草稿标题" # 创建草稿
hexo generate --draft # 生成包含草稿的静态文件以预览
hexo publish draft 草稿文件ID # 发布草稿
```

### 启动服务器

```shell
hexo server
```

更多信息: [Server](https://hexo.io/docs/server.html)

### 生成静态文件

```shell
hexo generate
```

更多信息: [Generating](https://hexo.io/docs/generating.html)

### 部署到远程站点

```shell
hexo deploy
```

更多信息: [Deployment](https://hexo.io/docs/one-command-deployment.html)
