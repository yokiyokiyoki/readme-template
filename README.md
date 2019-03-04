[English](./README.EN.md) | 简体中文

<p align="center"><img width="100" src="https://vuejs.org/images/logo.png"></p>

<p align="center">
  <a href="https://circleci.com/gh/vuejs/vue/tree/dev"><img src="https://img.shields.io/circleci/project/github/vuejs/vue/dev.svg" alt="Build Status"></a>
  <a href="https://codecov.io/github/vuejs/vue?branch=dev"><img src="https://img.shields.io/codecov/c/github/vuejs/vue/dev.svg" alt="Coverage Status"></a>
  <a href="https://npmcharts.com/compare/vue?minimal=true"><img src="https://img.shields.io/npm/dm/vue.svg" alt="Downloads"></a>
  <a href="https://www.npmjs.com/package/vue"><img src="https://img.shields.io/npm/v/vue.svg" alt="Version"></a>
  <a href="https://www.npmjs.com/package/vue"><img src="https://img.shields.io/npm/l/vue.svg" alt="License"></a>
</p>

<h2 align="center">ZARA - 下一代前端框架（主标题）</h2>
<p align="center"><b>基于 Web Components 并支持 IE8（简单介绍）</b></p>

# 目录

- [生态](#生态)
- [必须收藏的资源](#必须收藏的资源)
- [快速入门](#快速入门)
  - [安装](#安装)
  - [用法](#用法)
- [贡献者们](#贡献者们)
- [维护者](#维护者)
- [感谢](#感谢)
- [License](#license)

## 生态

[→ 生态学习路线图](https://github.com/Tencent/omi/tree/master/assets/rm.md)

| **项目**                                                                                                                                  | **描述**                       |
| ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------ |
| [ZARA-docs](https://github.com/Tencent/omi/blob/master/docs/main-concepts.cn.md)                                                           | 官方文档                       |
| [ZARA![](https://raw.githubusercontent.com/dntzhang/cax/master/asset/hot.png) ](https://github.com/Tencent/omi/tree/master/packages/omip) | 直接使用 ZARA 开发小程序！！！ |

### 特性

- 小巧的尺寸
- 支持 `TypeScript`

## 必须收藏的资源

- [你必须收藏 ES6 Spread Operator 技巧](https://github.com/Tencent/omi/blob/master/tutorial/spread-operator.cn.md)
- [使用 requestIdleCallback](https://div.io/topic/1370)

## 快速入门

### 安装

```bash
$ npm i zara-cli -g               # install cli
$ omi init my-app     # init project, you can also exec 'omi init' in an empty folder
$ cd my-app           # please ignore this command if you executed 'omi init' in an empty folder
$ npm start                      # develop
$ npm run build                  # release
```

目录说明:

```
├─ config
├─ public
├─ scripts
├─ src
│  ├─ assets
│  ├─ elements    //存放所有 custom elements
│  ├─ store       //存放所有页面的 store
│  ├─ admin.js    //入口文件，会 build 成  admin.html
│  └─ index.js    //入口文件，会 build 成  index.html
```

### 用法

```vue
<template>
  <Slider v-model="value" range />
</template>
<script>
export default {
  data() {
    return {
      value: [20, 50]
    };
  }
};
</script>
```

[→ simple demo](https://tencent.github.io/omi/packages/omi/examples/counter/)

## 贡献者们

<table>
    <tbody>
        <tr>
            <td>
                <a target="_blank" href="https://github.com/yokiyokiyoki"><img width="60px" src="https://avatars1.githubusercontent.com/u/20388810?s=460&v=4"></a>
            </td>
        </tr>
    </tbody>
</table>

## 维护者

- [yoki](https://github.com/yokiyokiyoki)

## 感谢

- [README-templete](https://github.com/yokiyokiyoki/readme-template)

## License

- [MIT](https://opensource.org/licenses/MIT)
