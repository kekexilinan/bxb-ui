# bxb UI —— 一个 Vue UI 组件
<!-- [![Build Status](https://travis-ci.org/harvey20/bxb-ui.svg?branch=master)](https://travis-ci.org/harvey20/bxb-ui) -->
[![NPM](https://img.shields.io/npm/v/bxb-ui-vue)](https://npmjs.org/package/bxb-ui-vue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 关于项目
bxb UI 是一个基于Vue2.0 + Sass 的 简易UI组件库，涵盖了Button、Icon、Toast、Tabs、Collapse、Popover等组件。
开发这套组件的目的主要是为了学习与提高，同时可以将自己的成功分享出来帮助到开源社区的开发者。<br>

## 开发者
* Harvey
* [gitee](https://gitee.com/harvey20)


## 安装
### 搭建Vue的开发环境
```sh
vue create hello-world
```
> 如果你还没有安装vue-cli，请先安装[vue-cli](https://cli.vuejs.org/zh/guide/installation.html)，再进行下一步。
### 安装 bxb UI
```sh
yarn add bxb-ui-vue
#or
npm install bxb-ui-vue --save
```
## 环境配置
### 样式引入
```js
import 'bxb-ui-vue/dist/index.css'
```
### 组件注册
```html
<script>
import 'bxb-ui-vue/dist/index.css'
import {Button} from 'bxb-ui-vue'
export default {
  name: 'yourApp',
  components: {
    Button
  }
}
</script>
```
### 使用第一个Button组件
```html
<Button>第一个的按钮</Button>
```

## 文档
[文档链接](http://harvey20.gitee.io/bxb-ui/)
## 提问

## 变更记录

## 联系方式

邮箱：harvey20@foxmail.com

## 贡献代码
Pray


