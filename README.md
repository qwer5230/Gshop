# Gshop(彪彪外卖)
## 项目介绍
1)	此项目为外卖Web App (SPA)
2)	包括商家, 商品, 购物车, 用户等多个子模块
3)	使用Vue全家桶+ES6++Webpack+Axios等前端最新最热的技术
4)	采用模块化、组件化、工程化的模式开发

## 彪彪外卖账号
### 用户名：123
### 密码：123

## dist启动命令
 yarn serve / npm run serve

## gshop-server服务器启动命令
yarn start / npm run start

## 项目难点
1. 页面刷新后better-scroll失效（创建的时机不对，利用watch+nextTick解决）
2. 用户7天免登陆(利用token向服务器发送请求)
3. 用户刷新页面后购物数据依然存在（把数据保存在loaclstorage，解决Vuex数据丢失问题）
4. 订餐组件导航栏如何做到互相影响(获取top值，计算对应的index)

