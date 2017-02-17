# vue-spa-project
> 教务管理系统 demo。基于vue.js技术栈，采用MVC等分层结构设计、数据解耦设计、UI组件化和自动构建的单页应用项目。

技术栈

- vue.js（2.0）
- vuex（状态管理）
- vue-router（前端路由）
- fetch（ajax的替代技术，更加高效地进行网络请求）
- element-ui（基于vue的PC端UI组件库）


基于Webpack的自动化

- ESlit代码质量控制，所有代码编写必须按照标准规范才能通过，并避免一些低级错误；
- 本地开发服务器监听文件修改，自动编译和刷新浏览器
- 测试服务器自动部署deploy（需要在服务器上启动一个node写的接收脚本）


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

