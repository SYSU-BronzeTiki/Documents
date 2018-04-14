# 需求规格说明文档

## 1. 引言
### 1.1 目的
通过该文档给出项目的整体结构以及功能结构

### 1.2 开发背景
本次开发的系统是基于微信公众号的电影购票系统。主要是为了满足用户使用微信直接完成一次观影前后的查询、选座、购票、支付、评价一系列的需求。通过微信公众号网页减少了用户额外使用一个专门的app的成本，简化操作，安全，高效。
。

## 2. 项目概述
### 2.1 产品描述
通过开发基于微信公众号平台的网页应用实现用户在微信平台下完成电影相关信息查询，电影票选座，订票，支付，对电影进行评分，参与电影讨论等操作。

### 2.2 产品功能
* 电影相关信息查询
  * 当前正在上映电影
  * 即将上映电影
  * 已上映电影
* 电影票选址、选场次、选座位
* 下订单
* 支付订单
* 电影评分，评论

### 2.3 用例分析

用户注册登陆，登陆后可以修改个人信息，如个人昵称，个人签名等

![login](https://raw.githubusercontent.com/SYSU-BronzeTiki/Documents/master/image/login.png)

用户登陆之后，可以使用应用的搜索功能，通过输入搜索字，可以获取到与搜索词相关联的电影信息，

，同时用户还会接收到当前正在上映的电影以及系统推荐的电影。

![movie_detail](https://raw.githubusercontent.com/SYSU-BronzeTiki/Documents/master/image/movie_detail.png)

用户在选定一部正在上映的电影后，通过选定电影院，场次，座位号来生成电影票订单，同时，利用微信提供的接口，完成支付。

![buy_ticket](https://raw.githubusercontent.com/SYSU-BronzeTiki/Documents/master/image/buy_ticket.png)



用户可以对一部电影进行评分并参加电影内容的相关讨论，也可以发表个人的评论。

![comment](https://raw.githubusercontent.com/SYSU-BronzeTiki/Documents/master/image/comment.png)