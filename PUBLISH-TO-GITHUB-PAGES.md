# 发布到 GitHub Pages

这个文件夹已包含自动发布配置。发布后，任何人都可以打开、复制网址并使用网站。

## 首次发布（约 3 分钟）

1. 登录 GitHub，点击右上角 **+**，选择 **New repository**。
2. 仓库名建议填写 `ltzb-alliance-ledger`，可见性选择 **Public**，然后创建仓库。
3. 在仓库页面选择 **uploading an existing file**，把本文件夹内的所有文件和 `.github` 文件夹拖进去后提交。注意上传的是文件夹内的内容，而不是外层文件夹本身。
4. 打开仓库的 **Settings → Pages**，在 **Build and deployment** 的 **Source** 中选择 **GitHub Actions**。
5. 等待约一分钟，进入 **Actions**，看到“发布率土同盟战报台账”成功完成后，GitHub Pages 页面会显示公开网址。

默认网址会是：

`https://你的GitHub用户名.github.io/ltzb-alliance-ledger/`

## 让搜索引擎更容易找到

- 网站已带有页面标题、简介、关键词和允许收录的 `robots.txt`。
- 发布成功后，将公开网址提交到百度搜索资源平台和 Google Search Console，可加快收录；自然收录没有固定时间。
- 要使用自定义域名，可在 GitHub **Settings → Pages → Custom domain** 填写你的域名；域名解析完成后，网站仍会自动更新。

## 重要说明

- 这是公开静态网站，但每位访问者的盟员和战报数据仍独立保存在各自浏览器中，不会相互看到，也不会上传到 GitHub。
- 如果希望多个管理共享同一份实时数据，需要再接入登录与数据库服务；GitHub Pages 本身只负责公开展示网页。
