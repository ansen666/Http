# Http

HTTP (Hypertext Transfer Protocol )，是Web联网的基础，也是手机联网常用的协议之一，HTTP协议是建立在TCP协议之上的一种协议。简单点来说就是客户端和服务器端之间数据传输的格式规范。

HTTP协议的特点：
- 支持B/S及C/S模式
- 简单快速：客户向服务器请求服务时，只需传送请求方法和路径。请求方法常用的有GET、HEAD、POST
- 灵活：HTTP 允许传输任意类型的数据对象。正在传输的类型由Content-Type 加以标记
- 无状态：HTTP 协议是无状态协议。无状态是指协议对于事务处理没有记忆能力。缺少状态意味着如果后续处理需要前面的信息，则它必须重传，这样可能导致每次连接传送的数据量增大

Http协议包括两个具体的请求方式Get以及Post,他们的主要区别有以下几点:
- Get通常是从服务器上获取数据，Post通常是向服务器传送数据
- Get把参数拼接在URL后面，Post传参方式是将参数作为http请求的内容，发送到指定的URL中去。
- Get传送数据量比较小，最多只能是2048字节(不同浏览器略有区别)。Post传送的数据量较大，一般被默认为不受限制。
- Get安全性非常低，Post安全性较高。

一般企业开发中，查找用Get请求，增加、删除、修改用Post请求。

# 本Demo有以下内容:
- 使用Get方式向服务器提交数据
- 使用Post方式向服务器提交数据
