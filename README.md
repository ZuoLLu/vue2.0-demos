
<h2>vue一些知识点整理</h2>

- [vue生命周期](#vue生命周期)
- [vue原理解析](#vue原理解析)
- [vue与react对比](#vue与react对比)
- [vue服务端渲染](#vue服务端渲染)
- [vue常用的一些方法](#vue常用的一些方法)

### vue生命周期
图片来源 https://segmentfault.com/a/1190000008010666

![vue生命周期](/img/demo-1.png)
### vue原理解析
  - [mvvm篇](https://github.com/qianyinghuanmie/interestingJs/tree/master/mvvm)
### vue与react对比

  参考[Vue与React比较](https://juejin.im/post/5b90be7e6fb9a05d0d284a49)
  - 生命周期的不同
  - 模板的不同  JSX vs Templates
  - 状态管理 vs 对象属性

    *React在state状态管理存储数据的，不能修改数据，修改数据在Setstate中setState是异步的，如果需要马上利用结果，需要在setState传入回调，具体可以看看React中setState几个现象---先知道再理解在Vue中，state对象并不是必须的，数据由data属性在Vue对象中进行管理。*`

### vue服务端渲染

  - [Vue.js 服务器端渲染指南](https://ssr.vuejs.org/zh#%E4%BB%80%E4%B9%88%E6%98%AF%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AB%AF%E6%B8%B2%E6%9F%93-ssr-%EF%BC%9F)
  - [vue-hackernews-2.0](https://github.com/vuejs/vue-hackernews-2.0/)

### vue常用的一些方法
    - vue指令

    ```
      // 注册一个全局自定义指令 `v-focus`
      Vue.directive('focus', {
      // 当被绑定的元素插入到 DOM 中时……
      inserted: function (el) {
        // 聚焦元素
        el.focus()
      }
    })

    ```

<h3 class="myH3">(更新于 2019-5-11)</h3>
<h5><a href="./Log">更新日志</a></h5>

![image](https://qianyinghuanmie.github.io/vue2.0-demos/dist/static/help1.gif)

<h3 class="myH3">Construction</h3>
<p>使用vue-cli开始构建, ，<a href="https://github.com/vuejs/vue-cli">关于 vue-cli</a></p>
<p>使用 vue-router 路由，<a href="https://github.com/vuejs/vue-cli">关于 vue-router</a></p>
<!-- <p>Use vuex processing business <a href="https://github.com/vuejs/vuex">about vuex</a></p> -->
<p>使用 vue-resource<a href="https://github.com/pagekit/vue-resource">关于 vue-resource</a></p>
<p>使用 sass <a href="https://github.com/sass/sass">关于 sass</a></p>
<p>基于 element-ui ，<a href="http://element.eleme.io/#/zh-CN/component/quickstart">关于 element-ui</a></p>
<p>基于 on mint-ui，<a href="https://github.com/ElemeFE/mint-ui">关于 mint-ui</a></p>
<p>使用 vue-touch（this gesture plug-in is another vue-touch branch and support vue2.0），<a href="https://github.com/vuejs/vue-touch/tree/next">关于 vue-touch</a></p>
<p>使用 阿里字体 ，<a href="http://www.iconfont.cn/home/index">关于 Ali font</a></p>
<h3 class="myH3">demos 列表</h3>
<p>1、城市排序和检索</p>
<p>2、高德地图的使用</p>
<p>3、v-charts的使用</p>
<p>4、使用 vue-picture-input 预览图片</p>
<p>5、使用 element-ui 的图片上组件</p>
<p>6、mintUi好用的组件集合 </p>
<p>7、vue-touch的使用</p>
<p>9、时间选择组件</p>
<h3 class="myH3">教程</h3>
<p>1、城市选择</p>
<p>2、高德地图的调用</p>
<p>3、高德地图的周边使用</p>

可以参考[my blog](http://www.cnblogs.com/star-wind/)

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

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
