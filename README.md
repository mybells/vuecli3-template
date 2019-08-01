# vuecli3Template

基于 vue-cli3.9.2 (2019-07-06) 的项目模板<br/>

技术栈主要使用 vue-cli3.0+vue+elementUI+vuex+vue-router+axios<br/>
并引入了 jquery,normalize.css,sass-loader

分支:<br/>
master: 只有前台模板（主线版本）<br/>
nodeclient: 包含前台和后台模板
<!-- TOC -->

- [vuecli3Template](#vuecli3template)
  - [目录结构](#目录结构)
  - [安装 npm 包](#安装-npm-包)
  - [运行项目](#运行项目)
  - [打包项目](#打包项目)
  - [导出 webpack 配置到 output.js](#导出-webpack-配置到-outputjs)

<!-- /TOC -->
## 目录结构

    |-- vuecli3Template
      |-- .gitignore
      |-- babel.config.js
      |-- package-lock.json
      |-- package.json
      |-- README.md
      |-- vue.config.js
      |-- public
      | |-- favicon.ico
      | |-- index.html
      |-- src
      |-- App.vue
      |-- main.js
      |-- api
      |-- assets
      | |-- logo.png
      | |-- 404_images
      | |-- 404.png
      | |-- 404_cloud.png
      |-- components
      | |-- HelloWorld.vue
      |-- plugins
      | |-- axios.js
      | |-- element.js
      |-- router
      | |-- router.js
      |-- store
      | |-- getters.js
      | |-- index.js
      | |-- modules
      | |-- app.js
      |-- styles
      |-- views
      |-- 404.vue
      |-- About.vue
      |-- Home.vue

## 安装 npm 包

```
npm install
```

## 运行项目

```
npm run serve
```

## 打包项目

```
npm run build
```

## 导出 webpack 配置到 output.js

```
vue inspect > output.js
```
