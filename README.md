# Vue项目移动端vm适配方案

> 解决的问题
- 处理引入的文件和资源路径的处理以及工作模式 postcss-import  postcss-url
- 压缩和清理代码 cssnano  
- css特性 兼容性处理 postcss-next
- 处理元素容器宽高比 postcss-aspect-ratio-mini
- 处理移动端1px的解决方案 postcss-write-svg
 
##  参考地址
[Vue项目中使用vw移动适配](https://www.w3cplus.com/mobile/vw-layout-in-vue.html)
[手淘过年项目使用到的前端技术](https://www.w3cplus.com/css/taobao-2018-year.html)

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

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
