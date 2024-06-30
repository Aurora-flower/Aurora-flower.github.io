---
layout: post
title: Asar
date: 2024-06-30 04:59:50
tags: [Asar]
---

ASAR 归档是一种专为 Electron 应用设计的简单的扩展存档格式，可以缓解 Windows 上长路径名的问题，加快 require 速度并隐藏源代码。

> Asar 是一种将文件夹结构打包成单个二进制文件的格式，通常用于将 Electron 应用程序的资源文件打包到一个文件中。
> 这样做可以方便地将所有资源文件打包到一个文件中，以便于分发和部署 Electron 应用程序。
>
> 使用 Asar 格式可以提高 Electron 应用程序的性能和安全性，因为它可以减少文件的数量和大小，并且可以防止用户轻易地修改应用程序的资源文件。
>
> Asar 格式的文件实际上是一个压缩文件，其中包含了原始文件夹结构以及额外的元数据信息。它可以通过特定的解压工具来解包，以便在运行时访问其中的资源文件。

