---
title: Hexo 的基本使用方式
date: 2025-06-07 11:58:47
tags: 
    - hexo
categories: 
    - Hexo
---


## 前言

> Hexo 是一个快速、简洁且高效的博客框架。
>
> Hexo 使用 Markdown（或其他标记语言）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。

---

## 创建博客项目

```shell
# 全局安装（命令工具）
npm install hexo-cli -g

# 局部安装（hexo 包）
npm install hexo

# 初始化一个博客项目
npx hexo [path]
```

---

## 基本操作

### 创建新文章

```shell
hexo new [layout] <title>
```

### 使用草图

草图是未发布的文章，可以通过以下命令查看和发布草图:

```shell
# 创建草稿
hexo draft <title>

# 生成包含草稿的静态文件以预览
hexo generate --draft 

# 发布草稿
hexo publish draft 草稿文件ID 
```

### 启动服务器

```shell
hexo server
```

### 生成静态文件

```shell
hexo generate
```

### 部署到远程站点

```shell
hexo deploy
```

---

## 相关链接

- [Hexo 官方文档 - 英文](https://hexo.io/docs/)
- [Hexo 官方文档 - 中文](https://hexo.io/zh-cn/docs)
- [Hexo 官方仓库](https://github.com/hexojs/hexo)
