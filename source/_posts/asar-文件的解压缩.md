---
layout: post
title: asar 文件的解压缩
date: 2024-06-30 04:58:07
tags: [Asar]
---


#### 安装 asar 工具

```shell
npm install -g asar
```


#### 压缩与解压

1. **解压**:

```shell
asar extract app.asar(源asar文件) app(目标解压文件夹)
```


2. **压缩**:

```shell
asar pack app(目标解压文件夹) app.asar(源asar文件)
```

---
**相关文档**：
[Electron Asar 归档](https://electron.nodejs.cn/docs/latest/tutorial/asar-archives/)