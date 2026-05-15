# Agent Developer Portfolio

🤖 个人主页，基于 GitHub Pages 部署

## 🚀 快速开始

1. **Fork 此仓库** 到你的 GitHub 账户
2. **编辑 `index.html`**：
   - 修改 `<title>` 中的名字
   - 修改 `h1` 标题为你的名字
   - 修改「关于我」部分
   - 更新技能标签
   - 添加你的项目链接
   - 修改联系方式
3. **启用 GitHub Pages**：
   - 进入 Settings → Pages
   - Source 选择 `main` 分支
   - 保存后等待部署

## 📝 自定义指南

| 修改内容 | 位置 |
|---------|------|
| 名字 | `index.html` 第 70 行 `<h1>` |
| 头像 | CSS 中 `.avatar::before` 改为图片或 emoji |
| 技能 | `.skills` 部分的 `<span>` 标签 |
| 项目 | `.projects-grid` 区域 |
| 链接 | `.links` 区域的 `<a>` 标签 |

## 🎨 主题色

修改 CSS 变量快速换色：
```css
:root {
    --accent: #00d4aa;      /* 主色调 - 科技绿 */
    --accent-secondary: #7c3aed;  /* 副色调 - 紫色 */
}
```

## 📄 许可证

MIT License
