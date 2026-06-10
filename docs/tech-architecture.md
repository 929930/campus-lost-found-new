# 校园失物招领平台 - 技术架构

## 架构设计

采用React单页应用架构，前端使用TailwindCSS进行样式设计，通过Mock数据和LocalStorage实现数据管理。

## 技术选型

- React@18 + Vite
- TailwindCSS@3
- Lucide React
- LocalStorage

## 路由定义

- / - 首页
- /detail/:id - 物品详情页
- /publish - 发布页面
- /profile - 个人中心

## 组件结构

Header、Hero、CategoryNav、ItemCard、ItemList、Sidebar、SearchBar、ImageGallery、StatusBadge、ContactButton、Footer

## 响应式断点

sm: 640px, md: 768px, lg: 1024px, xl: 1280px
