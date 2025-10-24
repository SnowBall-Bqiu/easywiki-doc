# easywiki 项目介绍文档

## 项目概述

easywiki 是一款面向个人或小型团队的轻量级知识库解决方案，旨在帮助用户快速构建和分享自己的知识体系。它以简洁易用为核心设计理念，无需复杂配置即可快速上手，让用户能够专注于内容创作本身。

![easyWIKI](https://github.com/user-attachments/assets/43f178a5-d614-4979-884e-fe165403067f)

## 核心功能

1. **Markdown 渲染**：支持 Markdown 格式内容编写与渲染，提升内容创作效率
2. **响应式设计**：完美适配 PC、平板和手机等各类设备，随时随地访问
3. **动态导航**：基于 `sidebar.json` 自动生成导航菜单，方便快捷
4. **安全可靠**：内容安全渲染，防止 XSS 攻击
5. **主题定制**：支持自定义 CSS 样式，打造个性化 Wiki 风格
6. **易用性**：无需复杂配置，快速上手，专注内容创作

## 技术栈

- **UI 框架**：Tailwind CSS - 一个实用优先的 CSS 框架，用于快速构建现代 Web 界面
- **Markdown 解析**：marked.js - 一个快速的 Markdown 解析器和编译器，用于将 Markdown 文本转换为 HTML
- **安全处理**：DOMPurify - 用于清理 HTML 和防止 XSS 攻击
- **前端交互**：原生 JavaScript 与 jQuery
- **后端支持**：PHP（可选，用于扩展功能）

## 项目结构

```
easywiki/
├── LICENSE               # 许可证文件(GNU GPL v3)
├── README.md             # 项目说明文档
├── favicon.ico           # 网站图标
├── index.html            # 主页面HTML
├── index.php             # PHP版本主页面
├── sidebar.json          # 侧边栏导航配置
├── tailwind.config.js    # Tailwind CSS配置
├── WxqqJump/             # 第三方登录相关组件
├── js/
│   └── app.js            # 主应用JavaScript
└── css/
    ├── app.css           # 应用样式
    └── wiki.css          # Wiki内容样式
```

## 快速开始

1. 点击左侧导航菜单浏览不同文档
2. 内容区域会实时渲染 Markdown 内容，方便阅读

详细部署信息和其他信息，请访问官方网站 [easywiki](https://easywiki.bq9.ru)

## 许可证

本项目采用 GNU General Public License v3.0 许可证开源，详细信息参见 LICENSE 文件。

## 定制与扩展

1. **导航定制**：通过修改 `sidebar.json` 文件可自定义导航菜单结构
2. **样式定制**：通过修改 `css/app.css` 和 `css/wiki.css` 可自定义界面样式
3. **功能扩展**：可基于现有代码结构添加新功能模块

easywiki 致力于为个人和小型团队提供简单、高效的知识管理解决方案，让知识管理变得轻松简单。