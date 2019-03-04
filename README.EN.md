English | [简体中文](./README.md)

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

- [Ecosystem](#Ecosystem)
- [Useful Resources](#Useful-Resources)
- [QuickStart](#QuickStart)
  - [Install](#Install)
  - [Usage](#Usage)
- [Contribution](#Contribution)
- [Maintainers](#Maintainers)
- [Thanks](#Thanks)
- [License](#license)

## Ecosystem

[→ 生态学习路线图](https://github.com/Tencent/omi/tree/master/assets/rm.md)

| **Project**                                                                                                                               | **Description**                |
| ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------ |
| [ZARA-docs](https://github.com/Tencent/omi/blob/master/docs/main-concepts.cn.md)                                                           | 官方文档                       |
| [ZARA![](https://raw.githubusercontent.com/dntzhang/cax/master/asset/hot.png) ](https://github.com/Tencent/omi/tree/master/packages/omip) | 直接使用 ZARA 开发小程序！！！ |

### Why Zara

- 小巧的尺寸
- 支持 `TypeScript`

## Useful-Resources

- [你必须收藏 ES6 Spread Operator 技巧](https://github.com/Tencent/omi/blob/master/tutorial/spread-operator.cn.md)
- [使用 requestIdleCallback](https://div.io/topic/1370)

## QuickStart

### Install

```bash
$ npm i zara-cli -g               # install cli
$ omi init my-app     # init project, you can also exec 'omi init' in an empty folder
$ cd my-app           # please ignore this command if you executed 'omi init' in an empty folder
$ npm start                      # develop
$ npm run build                  # release
```

Directory description:

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

### Usage

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

## Contribution

<table>
    <tbody>
        <tr>
            <td>
                <a target="_blank" href="https://github.com/yokiyokiyoki"><img width="60px" src="https://avatars1.githubusercontent.com/u/20388810?s=460&v=4"></a>
            </td>
        </tr>
    </tbody>
</table>

## Maintainers

- [yoki](https://github.com/yokiyokiyoki)

## Thanks

- [README-templete](https://github.com/yokiyokiyoki/readme-template)

## License

- [MIT](https://opensource.org/licenses/MIT)
