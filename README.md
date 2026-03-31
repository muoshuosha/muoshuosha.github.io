# muoshuosha.github.io

个人博客，基于 [Hexo](https://hexo.io/) 搭建，部署在 [GitHub Pages](https://muoshuosha.github.io/)。

## 发布文章

```bash
# 新建文章
npx hexo new "文章标题"

# 编辑 source/_posts/文章标题.md

# 本地预览
npx hexo server

# 发布
git add .
git commit -m "post: 文章标题"
git push
```

## 项目结构

```
├── source/_posts/   # 文章目录（Markdown）
├── themes/          # 主题
├── scaffolds/       # 模板
├── _config.yml      # 站点配置
└── .github/workflows/  # CI/CD（自动部署）
```

## 部署

推送 `main` 分支后，GitHub Actions 自动构建并发布到 GitHub Pages。
