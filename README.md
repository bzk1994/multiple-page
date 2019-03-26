# multiple-page

> 基于Vue的多页面脚手架，适用于访问量较大、并且对seo需求较高的项目

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
* master分支为常规配置
* router分支在多页面中增加了router路由，这种需求通常并不常见，只是为了解决 <b>多个公用性较高的雷同模块并且每个模块都有相同的多个页面</b> 的情况

举个🌰： 有多个分校网站，每个网站有两个页面，网站之间几乎完全相同，但会有微小的区别以及定制化的需求

此时单单使用多页面已经无法满足业务需求，结合每个多页面的 router 路由则可以切换 单个网站的两个页面

