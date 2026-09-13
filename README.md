# Jerry Sun's Main Page

个人主页与博客，使用自定义的极简「蓝白」模板（纯 HTML + 单个 CSS 文件，无外部依赖），托管在 GitHub Pages。

- 在线访问：<https://mikucy7.github.io/github-pages/>
- 本地预览：见 `../preview/`（与仓库同级的预览目录）

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

## 修改外观

- 配色/字体/间距都在 `assets/css/style.css` 顶部的 `:root` 变量里改；
- 页面结构在 `_layouts/`（`default.html` 是整体框架，`home.html`/`post.html`/`page.html` 分别是首页、文章页、普通页）；
- 站点标题、作者、邮箱在 `_config.yml`。
