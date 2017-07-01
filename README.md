# record

> A Vue.js project

<<<<<<< HEAD
## Build Setup
=======
## 说在前面
初学vue配合后台语言开发的时候，完全不知从何下手，网上的Demo更是少之又少。经过一段时间的学习积累，总算掳清vue单页面与服务器的关系，碰巧实训课程也有vue配合后台开发的要求，于是就动手做这个项目。

## 运行项目
>>>>>>> origin/master

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

<<<<<<< HEAD
For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
=======
## 使用技术
**`vue2.x`**+
**`vue-router`**+
**`vuex`**+
**`vue-resource`**+
**`vue-cli`**+
**`scss`**+
**`node.js`**+
**`express`**+
**`mongodb`**+
**`async`**+
**`es6`**

## 部分截图

### 登录注册
![](https://github.com/BYChoo/record/blob/master/static/show/start.gif)
![](https://github.com/BYChoo/record/blob/master/static/show/5.gif)

### 导入csv文件，登记缺勤学生，查看缺勤学生
![](https://github.com/BYChoo/record/blob/master/static/show/1.gif)
![](https://github.com/BYChoo/record/blob/master/static/show/2.gif)
![](https://github.com/BYChoo/record/blob/master/static/show/4.gif)

## 项目布局
```
.
├── api                                         // 服务器逻辑处理
├── build                                       // webpack配置文件
├── config                                      // 项目打包路径
├── src                                         // 源码目录
│   ├── components                              // 组件
│   │   ├── common                              // 公共组件
│   │   ├── calendar.vue                        // 日历组件
│   │   ├── check_work.vue                      // 查看缺勤组件
│   │   ├── cls_call.vue                        // 登记缺勤组件
│   │   ├── import_roster.vue                   // 导入组件
│   │   ├── login.vue                           // 租金组件
│   │   ├── register.vue                        // 注册组件
│   │   ├── restor.vue                          // 列表组件
│   │   ├── select_cls.vue                      // 选择班级组件
│   │   ├── select_restor.vue                   // 查看班级组件
│   ├── router
│   │   └── index.js                            // 路由配置
│   ├── store                                   // vuex的状态管理
│   │   ├── index.js                            // 引用vuex，创建store
│   │   ├── modules                             // store模块
│   │   └── mutations.js                        // 配置mutations
│   └── style
│       ├── common.scss                         // 公共样式文件
│       ├── mixin.scss                          // 样式配置文件
│       └── swiper.min.css
│   └── App.vue                                 // 页面入口文件
├── static                                      // 静态资源
│   ├── css                                     // css文件
│   ├── file                                    // 上传的csv文件
│   ├── fonts                                   // 字体图标
├── index.html                                  // 入口html文件
.
```
>>>>>>> origin/master
