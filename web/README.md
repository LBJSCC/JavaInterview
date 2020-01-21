# Web 篇
该篇章我们主要来介绍一些 Web 后端的知识，比如 http 协议， Cookie， Session， Jsp 等。

## [一次完整的HTTP请求过程](http-processing.md)

## Cookie 详解
首先我们需要介绍一下，在Web开发过程中为什么会引入Cookie。

我们知道Http协议是一种无状态协议， Web服务器本身不能识别出哪些请求是同一个浏览器发出的，浏览器的每一次请求都是完全孤立的。 

即便在Http1.1支持了持续连接，但当用户有一段时间没有提交请求时，连接也会自动关闭。

这时，作为Web服务器， 必须采用一种机制来唯一标识一个用户，同时记录该用户的状态。

于是就引入了第一种机制:Cookie机制。

Cookie机制: 采用的是在客户端保持Http状态的方案。

[Cookie详解](http://blog.tommyyang.cn/2017/03/13/Cookie详解-2017/)

## Session 详解
上面介绍了Cookie的相关知识，其中介绍了必须采用一种机制来唯一标识一个用户，同时记录该用户的状态。

于是就引入了第一种机制:Cookie机制;那么第二种就是Session机制。

Session机制：采用的是在服务器端保持Http状态信息的方案。

结合两篇博文也可以看出两种机制最明显的区别就是cookie是存储子在客户端,而Session是存储在服务器端。

[Session详解](http://blog.tommyyang.cn/2017/03/15/Session详解-2017/)

## [Spring 全家桶](spring.md)

## [Filter-Interceptor](filter-interceptor.md)