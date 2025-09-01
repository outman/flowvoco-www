# FlowVoco 官方网站

FlowVoco 是一款创新的英语学习应用，采用 Read-Along 模式，让英语学习变得更加高效和有趣。

## 技术栈

- **框架**: Astro.js
- **样式**: Tailwind CSS
- **图标**: Lucide Icons
- **字体**: Inter

## 功能特性

- 🏠 **主页**: 应用介绍、下载链接、联系方式
- 🌐 **多语言支持**: 中文和英文版本
- 📱 **响应式设计**: 完美适配移动端和PC端
- 🎨 **现代UI**: 采用 Linear 风格设计
- 📄 **法律页面**: 隐私政策和服务条款

## 页面结构

```
/
├── 首页 (index.astro)
├── zh-cn/
│   ├── privacy.astro (中文隐私政策)
│   └── terms.astro (中文服务条款)
└── en-us/
    ├── privacy.astro (英文隐私政策)
    └── terms.astro (英文服务条款)
```

## 开发指南

### 安装依赖

```bash
pnpm install
```

### 启动开发服务器

```bash
pnpm dev
```

### 构建生产版本

```bash
pnpm build
```

### 预览构建结果

```bash
pnpm preview
```

## 项目结构

```
src/
├── components/     # 可复用组件
│   ├── Header.astro
│   └── Footer.astro
├── layouts/        # 页面布局
│   └── Layout.astro
├── pages/          # 页面文件
│   ├── index.astro
│   ├── zh-cn/      # 中文页面
│   └── en-us/      # 英文页面
└── styles/         # 样式文件
    └── global.css
```

## 设计系统

网站采用 Linear 风格的设计系统，包括：

- 现代化的色彩方案
- 优雅的字体排版
- 一致的间距和圆角
- 平滑的过渡动画
- 响应式网格布局

## 浏览器支持

- Chrome (最新版本)
- Firefox (最新版本)
- Safari (最新版本)
- Edge (最新版本)

## 许可证

© 2025 FlowVoco. 保留所有权利。
