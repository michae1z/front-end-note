# cookie、session、token的使用场景

## 1 前言

### 无状态的HTTP协议

​		很久很久之前， Web基本都是文档的浏览而已。既然是浏览， 作为服务器， 不需要记录在某一段时间里都浏览了什么文档， 每次请求都是一个新的HTTP协议，就是请求加响应。不用记录谁刚刚发了HTTP请求， 每次请求都是全新的。

### 如何管理会话

随着交互式Web应用的兴起， 像在线购物网站，需要登录的网站等，马上面临一个问题，就是要管理回话，记住那些人登录过系统，哪些人往自己的购物车中放商品，也就是说我必须把每个人区分开。

本文主要讲解cookie，session, token 这三种是如何管理会话的。

## 2 正文

