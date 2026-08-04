# JiaxuanWang-th.github.io

基于 [Minimal Light](https://github.com/yaoyao-liu/minimal-light) 的个人主页（风格参考 [knightnemo.github.io](https://knightnemo.github.io/)）。

上线后地址：<https://jiaxuanwang-th.github.io/>

## 快速填写

| 文件 | 作用 |
|------|------|
| `_config.yml` | 姓名、职位、单位、邮箱、头像、社交链接 |
| `index.md` | About / News / Education / Projects / Experience 等正文 |
| `_data/publications.yml` | 论文列表 |
| `assets/img/avatar.png` | 替换为你的头像 |
| `assets/files/curriculum_vitae.pdf` | 可选，上传 CV 后在 `_config.yml` 取消 `cv_link` 注释 |

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库，命名为 **`JiaxuanWang-th.github.io`**（必须与用户名一致）。
2. 把本仓库推上去：

```bash
git remote add origin https://github.com/JiaxuanWang-th/JiaxuanWang-th.github.io.git
git branch -M main
git add .
git commit -m "Initial personal homepage from Minimal Light"
git push -u origin main
```

3. 打开仓库 **Settings → Pages**：
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
4. 等待 1–2 分钟，访问 <https://jiaxuanwang-th.github.io/>

## 本地预览（可选）

需要安装 [Ruby](https://www.ruby-lang.org/) 与 [Jekyll](https://jekyllrb.com/)：

```bash
bundle install
bundle add webrick
bundle exec jekyll serve
```

浏览器打开 <http://localhost:4000>。

## 致谢

- Theme: [yaoyao-liu/minimal-light](https://github.com/yaoyao-liu/minimal-light)
- Layout inspired by [KnightNemo](https://knightnemo.github.io/)
