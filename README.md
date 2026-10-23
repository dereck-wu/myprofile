<img src="assets/icon.svg" width="64" height="64" alt="">

# myprofile

个人主页，纯静态页面，发布到 GitHub Pages（无需域名）。

## 结构

- `index.html`：首页（简介、最近文章、经历、联系方式）
- `blog/index.html`：博客索引，每篇文章链接到 X 上的文章
- `style.css`：古早网页风格样式
- `.github/workflows/pages.yml`：push 到 `main` 后自动发布

## 维护

- 新增文章：在 `blog/index.html` 列表最前面加一个 `<li>`
- 更新经历：编辑 `index.html` 的「经历」部分
- 更换联系邮箱：替换 `index.html` 中的 `your-email@example.com`

没有 CMS，没有构建步骤，直接改 HTML 即可。
