# Vue.js打造一个开源的CNode社区

Vue.js打造一个开源的CNode社区，实现了浏览、发帖、收藏、回复、点赞、个人中心等等功能。

## 技术栈
* **Vue2.0**：前端页面展示。
* **Vuex**：Vuex，实现不同组件间的状态共享
* **vue-router**：页面路由切换
* **axios**：一个基于 `Promise` 的 HTTP 库，向后端发起请求。
* **Express**、**Koa2**：因为vue-cli生成的项目是基于**express**的，所以在开发阶段我使用的是它，但是真正上线生产环境我换成了**Koa2**。
* **Moment.js**：一个时间处理的库，方便对时间进行格式化成需要的格式，如主题、回复时间显示"* 分钟前、* 小时前、*天前"等等。
* **ES6**、**ES7**：采用ES6语法，这是以后的趋势。箭头函数、Promise等等语法很好用。
* **localStorage**：保存用户信息。
* **Canvas**：页面顶部小雪花效果。
* **Webpack**：vue-cli自带Webpack，但是需要自己改造一下，比如要对需要安装sass相关loader，vue-cli已经配置好了webpack，你只需要安装依赖就可以，使用的时候只需要`<style lang="scss"></style>`。
* **SASS**(**SCSS**)：用SCSS做CSS预处理语言，有些地方很方便，个人很喜欢用。
* **flex**：flex弹性布局，**简单**适配手机、PC端。
* **CSS3**：CSS3过渡动画及样式。


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


