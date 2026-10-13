# 14 天后端冲刺打卡

这是一个纯静态站点，入口文件为 `index.html`，无需后端服务。

## 三种上线方式

### GitHub Pages

把仓库推送到 GitHub，然后在仓库 Settings > Pages 中选择 GitHub Actions，仓库内的工作流会发布 `site/` 目录。

### Netlify

将仓库导入 Netlify，发布目录设置为 `site`，无需构建命令。

### Vercel

将仓库导入 Vercel，Root Directory 设置为 `site`，Framework Preset 选择 Other，无需构建命令。

## 本地预览

直接双击 `index.html`，或在当前目录启动任意静态文件服务器。