# standardProjectTemplate

一套规范的 Vue3.x 项目工程环境

搭建过程：https://juejin.cn/post/6951649464637636622

# vite-vue3-template

## npm init @vitejs/app

## ✔ Select a variant: › vue-ts

## npm i

## npm run dev

---

集成 Vue Router、Vuex、Element Plus、Axios、Stylus/Sass/Less

# 规范目录结构

├── publish/

└── src/
├── assets/ // 静态资源目录
├── common/ // 通用类库目录
├── components/ // 公共组件目录
├── router/ // 路由配置目录
├── store/ // 状态管理目录
├── style/ // 通用 CSS 目录
├── utils/ // 工具函数目录
├── views/ // 页面组件目录
├── App.vue
├── main.ts
├── shims-vue.d.ts

├── tests/ // 单元测试目录
├── index.html
├── tsconfig.json // TypeScript 配置文件
├── vite.config.ts // Vite 配置文件
└── package.json
