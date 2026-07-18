# JX95 的个人博客

- 站点地址：<https://jx15.github.io>
- 基于 Jekyll，托管在 GitHub Pages，推送到 `main` 分支后由 GitHub Actions 自动构建部署。
- 主题来自 [Tw93](https://tw93.fun/) 的 [cosy-jekyll-theme](https://github.com/tw93/tw93.github.io)，MIT License，保留原作者署名，感谢开源。

## 写文章

在 `_posts/` 下新建 `YYYY-MM-DD-标题.md`，front matter 示例：

```yaml
---
layout: post
title: 文章标题
category: 分类
summary: 一句话摘要
---
```

## 本地预览

```bash
bundle install
bundle exec jekyll serve
# 打开 http://127.0.0.1:4000
```
