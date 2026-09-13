# Jerry Sun's Main Page

个人主页与博客，基于 [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll) 模版，托管在 GitHub Pages。

- 在线访问：<https://mikucy7.github.io/github-pages/>

## 写新文章

在 `_posts/` 目录下新建 `YYYY-MM-DD-标题.md` 文件（日期必须保留在文件名最前面）：

```markdown
---
title: "文章标题"
date: 2026-09-13
---

正文内容，支持 Markdown。
```

提交并推送到 `main` 分支后，GitHub Pages 会自动重新构建，一两分钟后刷新页面即可看到新文章。

## 修改站点外观

站点标题、导航栏、配色、社交链接等都在 `_config.yml` 里改；导航栏头像在 `assets/img/` 里，替换后更新 `_config.yml` 中的 `avatar` 路径。
