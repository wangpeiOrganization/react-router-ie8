# react-redux-ie8-boilerplate

## 程序安装
### Node Version
```
nodejs 4.4.4
```
### 准备
```
npm install
// 设置淘宝镜像
npm config set registry https://registry.npm.taobao.org

// 设置显示npm安装进度
npm config set loglevel=http
```
### 开发
```
npm start #启动服务开发。
npm start:prod #启动服务生产环境开发（IE8调试）。
```
### 访问地址
http://localhost:3000
## 特性
* [react](https://github.com/facebook/react)
* [redux](https://github.com/rackt/redux)
* [react-router](https://github.com/rackt/react-router)
* [webpack](https://github.com/webpack/webpack)
* [webpack-dev-server](https://github.com/webpack/webpack-dev-server)
* [babel](https://github.com/babel/babel)
## 程序目录
```
build               打包生成文件位置
│
│      
doc                 说明文档
│       
│
node_modules        依赖包
│       
│
src                 源码目录
├── js           react组件目录
│   │
│   ├── component 开发组件目录
│   │
│   └── containers 页面用于显示的组件（复合组件）
│
├── router       react-router项目路由配置
│
├── images       公共图片文件夹
│
├── json         静态数据json文件夹
│
└── entry.js     项目进入的初始文件
│
│
.babelrc            babel配置文件
│
│
.gitignore          git提交ignore配置文件
│
│
package.json        项目依赖以及启动的配置文件
│
│
webpack.config.dev.js            开发配置文件
│
│
webpack.config.production.js     生产配置文件
```
## 兼容性
## 其它
- 该项目用于测试i8性能，可以当做脚手架使用
