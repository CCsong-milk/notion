# 📅 Notion Countdown + Progress Page

这是一个可嵌入到 Notion 的自定义倒计时 + 进度条页面，适合考研、考试、项目截止日等场景。

## 🚀 在线预览

> 请部署后将链接粘贴在此，例如：[https://your-name.vercel.app](https://pxl212.github.io/notion/)

## ✅ 功能说明

- 显示距离目标时间还剩多少天/小时/分钟
- 动态进度条，展示时间进度百分比
- 自适应布局，适配嵌入 Notion 页面

## 📦 部署方式

你可以将此项目部署到以下平台：

### 方法一：Vercel 部署（推荐）

1. 登录 [https://vercel.com](https://vercel.com)
2. 点击 **"New Project"**
3. 选择本仓库（notion）
4. 项目 Root Directory 选择：**根目录**
5. 构建设置：不需要，静态页面会自动识别
6. 部署成功后，将链接复制到 Notion 中 `/embed`

### 方法二：GitHub Pages 部署

1. 进入仓库设置 → Pages
2. Source 选择为 `main` 分支，文件夹选择 `/(root)`
3. 保存后，你会得到一个链接类似：
https://pxl212.github.io/notion/
4. 在 Notion 输入 `/embed` 插入该链接即可使用

---

## 📅 示例画面

![countdown preview](./preview.png)

---

> 如需修改起始时间和结束时间，可在 `index.html` 中修改如下部分：

```js
const startTime = new Date("2024-09-01T00:00:00");
const endTime = new Date("2024-12-23T00:00:00");
https://notion-countdown-pxl212.vercel.app

---

## ✅ 最终嵌入到 Notion

在 Notion 中：

1. 输入 `/embed`
2. 粘贴刚刚部署好的链接
3. 点击“创建嵌入内容”，即可显示你的倒计时 + 进度条页面

---
