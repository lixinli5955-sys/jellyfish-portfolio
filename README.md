# 水母 Jellyfish — 个人作品集

2026-11-14 黑色强调色定稿版。纯静态 HTML / CSS / JavaScript，无需安装依赖、构建、数据库或 API Key。

## 源码文件

- `index.html`：首页、项目板块、联系方式。
- `style.css`：布局、配色、手机适配与动效。强调色变量为 `--accent`。
- `app.js`：案例详情 `cases`、AI 工作方法 `flows`、图库 `gallery` 与页面交互。
- `assets/`：页面实际使用的海报、截图与合照。
- `.nojekyll`：让 GitHub Pages 直接发布静态文件。

ZIP 解压后的文件可直接作为仓库根目录。请保留 assets 文件夹结构；不要只上传 ZIP，也不要把所有文件再套一层文件夹。

## 部署到 GitHub Pages

1. 登录自己的 GitHub，创建一个 Public 仓库，名称可用 `jellyfish-portfolio`。
2. 上传本包解压后的全部文件到仓库根目录，并提交到 `main` 分支。根目录必须直接包含 `index.html`。
3. 打开仓库 `Settings → Pages`。
4. 在 `Build and deployment → Source` 选择 `Deploy from a branch`。
5. 选择 `main` 分支、`/(root)`，点击 `Save`。
6. 等待部署完成，以 Pages 页面显示的网址为准。通常是 `https://你的用户名.github.io/jellyfish-portfolio/`。
7. 用未登录 GitHub 的浏览器窗口打开该网址，确认他人可访问。

官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 日常修改

文案和图片路径在 index.html；案例弹窗文案在 app.js 的 cases；AI 方法在 flows；图片位于 assets。修改后提交到 main，GitHub Pages 会重新发布。

可将整个 ZIP 交给其他开发者或新的 AI 账号维护，不依赖当前 ChatGPT 对话。

## 查看与交互

直接打开 index.html 可以浏览。复制链接、复制微信等浏览器功能推荐在已部署的 HTTPS 站点验证。功能包括案例切换、图片放大与前后浏览、管理折叠面板、AI 方法切换、手机菜单和滚动动效。

联系方式默认折叠、点击后显示。公开部署后任何访客均可点击查看；折叠并非密码保护。

ChatGPT 中的私密预览与 GitHub Pages 是两个独立部署，本包不包含账号令牌或 ChatGPT 专属配置。
