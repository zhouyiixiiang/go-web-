# web编程

什么是http？

* 无状态、由文本构成的请求-响应协议
* 使用客户端-服务器计算模型
* 以纯文本方式发送和接收协议数据

客户端-服务器计算模型：

* 客户端向服务器发起会话
  * 用户代理
* 服务器为客户端提供服务
  * web服务器

无状态协议？

* 后续发送的请求对之前发送的请求一无所知

### http请求

由一系列文本行组成：

* request-line
  * 请求方法 url http版本
* header
  * host
  * user-agent
* 一个空行
* body(可选)

### 安全的请求方法

只是请求信息，不对服务器状态进行修改

### 浏览器对请求方法的支持

get：

* http方法

post：

* 通过添加html表单实现
* html的form标签中的method属性指定get或post

PUT、Delete：

* XMLHttpRequest（XHR）
  * 一系列浏览器API
  * 由Javascript包裹