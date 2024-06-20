<h1 align="center">Ant Design Pro Vue</h1>
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors)

<div align="center">
An out-of-box UI solution for enterprise applications as a Vue boilerplate. based on  <a href="https://vuecomponent.github.io/ant-design-vue/docs/vue/introduce-cn/" target="_blank">Ant Design of Vue</a>
</div>

<div align="center">

[![License](https://img.shields.io/npm/l/package.json.svg?style=flat)](https://github.com/sendya/ant-design-pro-vue/blob/master/LICENSE)
[![Release](https://img.shields.io/github/release/sendya/ant-design-pro-vue.svg?style=flat)](https://github.com/sendya/ant-design-pro-vue/releases/latest)
[![Travis branch](https://travis-ci.org/sendya/ant-design-pro-vue.svg?branch=master)](https://travis-ci.org/sendya/ant-design-pro-vue)

</div>

Overview
----

基于 [Ant Design of Vue](https://vuecomponent.github.io/ant-design-vue/docs/vue/introduce-cn/) 实现的 [Ant Design Pro](https://pro.ant.design/)  Vue 版

[预览地址](https://pro.loacg.com/)  **附带一些后台基础用到的列表展示例子**

![工作台-多标签模式](https://static-2.loacg.com/open/static/github/20190224163345.jpg)

![工作台+设置菜单](https://static-2.loacg.com/open/static/github/20181126112124.png)

![个人设置](https://static-2.loacg.com/open/static/github/20180916-134251.png)

![权限列表](https://static-2.loacg.com/open/static/github/20180916-154937.png)


环境和依赖
----

- node
- yarn
- webpack
- eslint
- @vue/cli ~3
- [ant-design-vue](https://github.com/vueComponent/ant-design-vue) - Ant Design Of Vue 实现
- [vue-cropper](https://github.com/xyxiao001/vue-cropper) - 头像裁剪组件
- [@antv/g2](https://antv.alipay.com/zh-cn/index.html) - Alipay AntV 数据可视化图表
- [Viser-vue](https://viserjs.github.io/docs.html#/viser/guide/installation)  - antv/g2 封装实现

> 请注意，我们强烈建议本项目使用 [Yarn](https://yarnpkg.com/) 包管理工具，这样可以与本项目演示站所加载完全相同的依赖版本 (yarn.lock) 。由于我们没有对依赖进行强制的版本控制，采用非 yarn 包管理进行引入时，可能由于 Pro 所依赖的库已经升级版本，而引入了新版本所照成的问题。作者可能会由于时间问题无法及时排查而导致您采用本项目作为基项目而出现问题。



项目下载和运行
----

- 拉取项目代码
```bash
git clone https://github.com/sendya/ant-design-pro-vue.git
cd ant-design-pro-vue
```

- 安装依赖
```
yarn install
```

- 开发模式运行
```
yarn run serve
```

- 编译项目
```
yarn run build
```

- Lints and fixes files
```
yarn run lint
```



其他说明
----

- **关于 Issue 反馈 (重要!重要!重要!) 请在开 *Issue* 时，描述清楚您的使用环境，所使用 Pro 版本或分支，出现的情况等...** 另外，若有疑问也可加入 QQ群 （Ant Design Vue 原作者使用讨论群 217490093，**非 Pro 群**），项目的几位维护者也在该群

- 项目使用的 [vue-cli3](https://cli.vuejs.org/guide/), 请更新您的 cli

- 关闭 Eslint (不推荐) 移除 `package.json` 中 `eslintConfig` 整个节点代码

- 项目使用了在线 mock，[easy-mock](https://www.easy-mock.com/)  项目所用的 mock 数据 [点击查看(请勿改动接口返回数据)](https://www.easy-mock.com/project/5b7bce071f130e5b7fe8cd7d)，也可以下载 [ANTD-PRO-Easy-Mock-API.zip](https://github.com/sendya/ant-design-pro-vue/files/2682711/ANTD-PRO-Easy-Mock-API.zip) 然后自行导入到自己的 mock 服务上

- 开启组件按需加载 `/src/main.js` L7 修改为 `import './core/lazy_use'`

- 修改 Ant Design 配色，在文件 `vue.config.js` 中，其他 less 变量覆盖参考 [ant design](https://ant.design/docs/react/customize-theme-cn) 官方说明
```ecmascript 6
  css: {
    loaderOptions: {
      less: {
        modifyVars: {
          /* less 变量覆盖，用于自定义 ant design 主题 */

          'primary-color': '#F5222D',
          'link-color': '#F5222D',
          'border-radius-base': '4px',
        },
        javascriptEnabled: true,
      }
    }
  }
```

Contributors
----

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars0.githubusercontent.com/u/5404542?v=4" width="100px;" alt="言肆"/><br /><sub><b>言肆</b></sub>](https://i.loacg.com)<br />[💻](https://github.com/sendya/ant-design-pro-vue/commits?author=sendya "Code") [📖](https://github.com/sendya/ant-design-pro-vue/commits?author=sendya "Documentation") | [<img src="https://avatars0.githubusercontent.com/u/25897806?v=4" width="100px;" alt="kokoroli"/><br /><sub><b>kokoroli</b></sub>](https://github.com/kokoroli)<br />[💻](https://github.com/sendya/ant-design-pro-vue/commits?author=kokoroli "Code") [📖](https://github.com/sendya/ant-design-pro-vue/commits?author=kokoroli "Documentation") | [<img src="https://avatars0.githubusercontent.com/u/10286849?v=4" width="100px;" alt="musnow"/><br /><sub><b>musnow</b></sub>](https://github.com/musnow)<br />[💻](https://github.com/sendya/ant-design-pro-vue/commits?author=musnow"Code") | [<img src="https://avatars0.githubusercontent.com/u/8555127?v=4" width="100px;" alt="zkwolf"/><br /><sub><b>zkwolf</b></sub>](https://github.com/zkwolf)<br />[💻](https://github.com/sendya/ant-design-pro-vue/commits?author=zkwolf"Code") | [<img src="https://avatars0.githubusercontent.com/u/19700237?v=4" width="100px;" alt="mcmf"/><br /><sub><b>土拨鼠</b></sub>](https://github.com/mcmf)<br />[💻](https://github.com/sendya/ant-design-pro-vue/commits?author=mcmf"Code") | [<img src="https://avatars0.githubusercontent.com/u/28291464?v=4" width="100px;" alt="AClumsy"/><br /><sub><b>阿凌</b></sub>](https://github.com/AClumsy)<br />[💻](https://github.com/sendya/ant-design-pro-vue/commits?author=AClumsy"Code") | [<img src="https://avatars0.githubusercontent.com/u/3831242?v=4" width="100px;" alt="mynuolr"/><br /><sub><b>mynuolr</b></sub>](https://github.com/mynuolr)<br />[💻](https://github.com/sendya/ant-design-pro-vue/commits?author=mynuolr"Code") |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
 [<img src="https://avatars0.githubusercontent.com/u/1051992?v=4" width="100px;" alt="since2006"/><br /><sub><b>since2006</b></sub>](https://github.com/since2006)<br />[💻](https://github.com/sendya/ant-design-pro-vue/commits?author=since2006"Code") | [<img src="https://avatars0.githubusercontent.com/u/26241263?v=4" width="100px;" alt="yihuishou"/><br /><sub><b>挥手的骑士</b></sub>](https://github.com/yihuishou)<br />[💻](https://github.com/sendya/ant-design-pro-vue/commits?author=yihuishou"Code") |
<!-- ALL-CONTRIBUTORS-LIST:END -->

附属文档
----

- [路由/菜单说明](https://github.com/sendya/ant-design-pro-vue/blob/master/src/router/README.md)
- [Table 重封装组件](https://github.com/sendya/ant-design-pro-vue/blob/master/src/components/table/README.md) [@AraragiTsukihiz](https://github.com/araragitsukihiz)
- [ANTD 默认配置项](https://github.com/sendya/ant-design-pro-vue/blob/master/src/defaultSettings.js)
- [按需加载/减少打包大小](https://github.com/sendya/ant-design-pro-vue/blob/master/docs/load-on-demand.md)  
- [为首屏增加 Loading 动画](https://github.com/sendya/ant-design-pro-vue/blob/master/docs/add-page-loading-animate.md)
- [多标签页组件 feature/multi-tabs](https://github.com/sendya/ant-design-pro-vue/tree/feature/multi-tabs) [如何移除](https://github.com/sendya/ant-design-pro-vue/blob/master/docs/multi-tabs.md)
- [按需加载用例 feature/demand_load](https://github.com/sendya/ant-design-pro-vue/tree/feature/demand_load)
- [多语言使用案例 feature/lang](https://github.com/sendya/ant-design-pro-vue/tree/feature/lang) [@musnow](https://github.com/musnow) 提供
- [为项目增加依赖项分析工具 analyzer](https://github.com/sendya/ant-design-pro-vue/blob/master/docs/webpack-bundle-analyzer.md)  
- ANTD PRO 额外组件
  - Trend 趋势标记 [Trend.md](https://github.com/sendya/ant-design-pro-vue/blob/master/src/components/Trend/index.md)
  - AvatarList 用户头像列表 [AvatarList.md](https://github.com/sendya/ant-design-pro-vue/blob/master/src/components/AvatarList/index.md)
  - CountDown 倒计时 [CountDown.md](https://github.com/sendya/ant-design-pro-vue/blob/master/src/components/CountDown/index.md)
  - Ellipsis 文本自动省略号 [Ellipsis.md](https://github.com/sendya/ant-design-pro-vue/blob/master/src/components/Ellipsis/index.md)
  - NumberInfo 数据文本 [NumberInfo.md](https://github.com/sendya/ant-design-pro-vue/blob/master/src/components/NumberInfo/index.md)
  - FooterToolbar 底部工具栏 [FooterToolbar.md](https://github.com/sendya/ant-design-pro-vue/blob/master/src/components/FooterToolbar/index.md)
  - IconSelector 图标选择组件 [IconSelector.md](https://github.com/sendya/ant-design-pro-vue/blob/master/src/components/IconSelector/README.md) 提供: [@AraragiTsukihiz](https://github.com/araragitsukihiz)
- 其他待补充...


备注
----

> @vue/cli 升级后，eslint 规则更新了。由于影响到全部 .vue 文件，需要逐个验证。既暂时关闭部分原本不验证的规则，后期维护时，在逐步修正这些 rules
## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/all-contributors/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!