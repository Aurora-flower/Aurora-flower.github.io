---
layout: post
title: Asar 文件的解压缩
date: 2024-06-30 04:58:07
categories: [扩展]
tags: [Asar, 扩展学习]
---


#### 安装 asar 工具

```shell
npm install -g asar
```


#### 压缩与解压

1. **解压**:

```shell
#  extract|e <archive> <dest>            extract archive
asar extract app.asar(源asar文件) app(目标解压文件夹)
```


2. **压缩**:

```shell
#  pack|p [options] <dir> <output>       create asar archive
asar pack app(目标解压文件夹) app.asar(源asar文件)
```


### 其他命令

1. **列出归档文件与目录**:

```shell
#  list|l [options] <archive>            list files of asar archive
asar list app.asar(源asar文件)
```

2. **提取单个文件**:

```shell
#  extract-file|ef <archive> <filename>  extract one file from archive
asar extract-file app.asar(源asar文件) file.*(目标文件)
```

---
**相关文档**：
[Electron Asar 归档](https://electron.nodejs.cn/docs/latest/tutorial/asar-archives/)