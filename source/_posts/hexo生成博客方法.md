---
title: hexo编辑博客的方法
date: 2017-11-02 21:05:51
tags: hexo
categories: 博客
---
基础的hexo博客使用方法
<!-- more -->
## 生成博客
### 首先用hexo生成新的md文件


```
hexo new "your_new_blog_name"
```

### 生成


```
hexo clean
hexo g
hexo s
```

## 换主题的方法：
### 下载主题资源

```
$ git clone https://github.com/iissnan/hexo-theme-next themes/next
```
### 更新下载主题到_config.yml
theme: next
<!--next是我们这次的主题名-->

### 生成
```
hexo clean
hexo g
hexo s
```


