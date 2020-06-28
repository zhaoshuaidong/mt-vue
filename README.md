# 说明

本项目是用vue开发的，模仿美团网


- 技术栈
 - 使用@vue/cli构建项目
 - 使用vue vue-router来渲染UI界面
 - 采用vuex来管理状态数据
 - 本地模拟数据，封装axios来请求本地文件
 - UI库使用element-ui
 - 使用css预编译器less

# 目录结构
|--public               项目公开目录
|--src                  src开发目录
|   |--assets           静态资源
|   |--axios            请求文件
|   |--components       公共组件
|   |--plugins          element-ui相关资源
|   |--router           路由配置
|   |--store            数据管理
|   |--views            页面级组件
|   |--main.js          主入口文件
|   |--vue.config.js    配置文件    

# CLI构建命令

##### 初始化依赖配置
- npm i

#### 启动项目 
- npm run serve