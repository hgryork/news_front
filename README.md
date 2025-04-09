# 新闻检测前端项目

## 项目简介

本项目是一个基于Vue3的新闻检测系统前端项目，提供新闻内容的检测、分析和管理功能。

## 技术栈

- Vue 3
- Vite
- Vue Router
- Vuex
- Element Plus
- Axios

## 主要功能

- 用户认证与授权
- 新闻内容检测
- 系统监控
- 文件上传与管理
- 多环境配置支持

## 项目结构

```
├── src/                # 源代码目录
│   ├── api/           # API接口
│   ├── assets/        # 静态资源
│   ├── components/    # 公共组件
│   ├── layout/        # 布局组件
│   ├── router/        # 路由配置
│   ├── store/         # 状态管理
│   ├── utils/         # 工具函数
│   └── views/         # 页面视图
├── public/            # 公共资源
├── vite/              # Vite配置
└── vite.config.js     # Vite主配置文件
```

## 开发环境设置

1. 安装依赖
```bash
npm install
```

2. 启动开发服务器
```bash
npm run dev
```

3. 构建生产版本
```bash
npm run build
```

## 环境配置

项目支持多环境配置：
- `.env.development`: 开发环境配置
- `.env.production`: 生产环境配置
- `.env.staging`: 测试环境配置

## 项目特性

- 基于Vue3最新特性开发
- 使用Vite构建工具，提供更快的开发体验
- 集成Element Plus UI组件库
- 支持SVG图标动态加载
- 完善的权限管理系统
- 响应式设计，支持多端适配

## 开发规范

- 遵循ESLint代码规范
- 使用Prettier进行代码格式化
- 组件化开发
- 模块化管理

## 浏览器支持

- 推荐使用最新版本的Chrome、Firefox、Safari浏览器
- 支持现代浏览器的最新两个版本