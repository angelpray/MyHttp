# MyHttp

# HTTP基础

## 1.HTTP概述

### 问题
1. WEB客户端和服务器是如何通信的
2. 表示web内容的资源来自何方
3. web事务是怎样工作的
4. HTTP通信使用的报文格式
5. 底层TCP网络传输
6. 不同的HTTP协议变体
7. 因特网上安装的大量HTTP架构组件的一部分

### HTTP
HTTP,Hypertext Transfer Protocol,超文本传输协议,是在万维网上进行通信所使用的协议方案.HTTP有很多应用,但最著名的是用于web浏览器和web服务器(相关的web应用程序)之间的**双工通信**

HTTP使用的是可靠的数据传输协议,因此即使数据来自地球的另一端,它也能确保数据在传输过程中不会被损坏或产生混乱.

### web客户端和服务器
Web内容都是存储在Web服务器上的。Web服务器所使用的是HTTP协议，因此经常会被称为HTTP服务器。这些HTTP 服务器存储了因特网中的数据，如果HTTP 客户端发出请求的话，它们会提供数据。客户端向服务器发送HTTP 请求，服务器会在HTTP 响应中回送所请求的数据.HTTP 客户端和HTTP服务器共同构成了万维网的基本组件。

![https://images.cnblogs.com/cnblogs_com/wljqds/1843794/o_200908095436clientAndServer.PNG](clientAndServer)


