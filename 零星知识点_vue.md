学习时间

早： 6:00-8:30

白：9:00-10:30

晚：7:00-10:30



下午玩

一、全局变量和局部变量一旦同名，全局变量是不会作用于同名局部变量的作用域

# 首屏图片懒加载

#三次握手，四次挥手

第一次 客户端向服务器发送SYN标识符+J序号，客服端变为send状态

第二次 服务端接收到请求，向客户端发送SYN K 及ACK J+1 ，服务端进入 请求已接收，等待确认阶段

第三次 客户端接收到请求，向服务端发送ACK K+1 ,确认连接

#eventLoop机制

#vue生命周期

beforeCreated/created/beforeMounted/mounted

beforeUpdate/updated/beforeDestory/destoryed

#vue设置key的作用

不设置情况下，会直接复用，造成业务异常

- 比如tab切换列表页面，选中后变为已读状态，第一个列表第二项变了以后，会影响第二个列表的第二项；解决办法就是设置不同的key值

#vue3是否了解

#DOM Diff

对比两个虚拟节点找差异，

#vue优化

- source Map

- keep-alive

- CDN引入

- key值

- 

# 防抖节流函数（自己能直接写出来那种）

# Promise

# async await

await和promise是连在一起使用的，await 在等待promise的返回值

# vue-router

# vuex（state\mutations\actions\modules\getters）

state 中央数据管理

mutations 修改中央数据

antions 异步请求修改中央数据？

getter 处理中央处理 返回需要结果

# axios 封装



#vue 文件

.browsers 浏览器配置文件

.babel.config.js  babel配置文件

.postcss.config.js  css预处理器

.package-lock.js 锁定package.json 编译版本

# export default /export /modules exports区别

# vue 计算属性和侦听器（vue官方）