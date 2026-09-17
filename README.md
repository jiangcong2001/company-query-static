# 企查助手 · GitHub Pages 静态版

这是原 ThinkPHP 企业信息查询源码的**无 PHP/MySQL 静态改造版**，适合免费发布到 GitHub Pages。保留了企业查询、风险摘要和 AI 风格分析界面，使用本地 JSON 演示数据和浏览器本地存储。

## 重要边界

本版本不连接真实工商数据库，不包含用户登录、后台、支付、会员、真实在线 AI API 或服务端数据写入。这样可以避免在 GitHub Pages 暴露第三方 API 密钥。数据仅用于演示，不构成商业、投资或法律建议。

## 发布

把本目录内容推送到 GitHub 仓库，并在仓库 Settings → Pages 中选择 `Deploy from a branch`、`main`、`/ (root)`，保存后等待 GitHub Pages 发布。

## 数据更新

编辑 `data/companies.json` 后提交到 GitHub，页面会自动使用新的静态数据。
