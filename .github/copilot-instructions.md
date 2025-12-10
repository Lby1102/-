# Copilot Instructions for AI Coding Agents

## 项目概述
这是一个部署在 GitHub Pages 的临时门户网站项目，使用纯静态 HTML/CSS/JavaScript 构建。

**部署地址**: https://lby1102.github.io/-/  
**GitHub 仓库**: https://github.com/Lby1102/-.git

## 架构与技术栈
- **前端**: 纯静态网站 (HTML5 + CSS3 + Vanilla JavaScript)
- **部署**: GitHub Pages (从 main 分支自动部署)
- **版本控制**: Git

## 项目结构
```
临时门户网站/
├── index.html          # 主页面 - 包含所有页面内容
├── styles.css          # 全局样式 - 渐变背景、响应式设计
├── script.js           # 交互脚本 - 平滑滚动、时间显示
└── README.md           # 项目文档
```

## 关键开发工作流

### 更新并部署网站
```powershell
git add .
git commit -m "描述更改内容"
git push origin main
```
推送后 GitHub Pages 会自动重新部署（约 1-2 分钟）

### 本地预览
- 直接在浏览器打开 `index.html`
- 或使用 VS Code Live Server 扩展实时预览

## 设计约定
- **配色方案**: 紫色渐变主题 (#667eea → #764ba2)
- **响应式**: 在 768px 断点适配移动设备
- **导航**: 使用锚点链接 + 平滑滚动效果
- **中文优先**: 所有文本内容使用简体中文

## 常见任务

### 添加新页面内容
在 `index.html` 的 `<main>` 中添加新的 `<section>` 元素，并在导航中添加对应链接。

### 修改样式
编辑 `styles.css` - 主要颜色变量在 section 和 header 的 background 属性中。

### 添加交互功能
在 `script.js` 中添加事件监听器，遵循现有的 vanilla JavaScript 模式。

## 重要提醒
- 这是静态网站，无后端服务器或数据库
- 所有更改需通过 Git 推送才能在线上生效
- GitHub Pages 仅支持静态内容，不支持服务器端代码

---
_更新时间: 2025年12月10日_
