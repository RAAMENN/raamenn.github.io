# raamenn.github.io

个人主页，地址：<https://raamenn.github.io/>

纯静态页面，只有 HTML 和 CSS，没有框架，也不需要构建。`master` 分支上的文件就是线上的网站，推送后 GitHub Pages 会自动更新。

## 文件

| 文件 | 作用 |
|---|---|
| `index.html` | 主页的全部内容 |
| `style.css` | 样式，颜色集中定义在文件开头 |
| `404.html` | 访问不存在的地址时显示的页面 |
| `images/avatar.jpg` | 头像 |
| `favicon.png`、`apple-touch-icon.png` | 浏览器标签页图标和手机主屏图标 |
| `.nojekyll` | 告诉 GitHub Pages 直接托管文件，不要删 |

## 改内容

所有内容都在 `index.html` 里，搜索 `EDIT` 能找到三处需要填写的地方：

1. **简介**：`<p class="bio">` 里的那段文字。
2. **项目**：每个项目是一个 `<li>`，改链接、名字和一句话描述；复制整个 `<li>` 可以再加一个。
3. **链接**：`<ul class="links">` 里每行一个，可以增删。

可以直接在 GitHub 网页上点开文件编辑并提交。

## 本地预览

```bash
python3 -m http.server 8000
```

然后打开 <http://localhost:8000/>。

## 换头像

把新图片裁成正方形，覆盖 `images/avatar.jpg`（建议 384×384 左右）。标签页图标是 `favicon.png`（64×64）和 `apple-touch-icon.png`（180×180），需要的话一起换。
