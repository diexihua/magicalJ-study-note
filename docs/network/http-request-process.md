# 浏览器端发起HTTP请求流程

## 1. 构建请求

1. 览器从地址栏的输入中获得服务器的IP地址和端口号；
2. 如果不是ip地址那就肯定是域名了，于是就会发起域名解析动作，通过访问一系列的域名解析服务器，试图把这个域名翻译成TCP/IP协议里的IP地址。

[DNS](https://github.com/mrmagicalJ/magicalJ-study-note/blob/master/DNS.md)

## 2. 查找缓存

## 3. 准备 IP 地址和端口

## 4. 等待 TCP 队列

## 5. 建立 TCP 连接

如果请求是HTTPS，还需要建立TLS连接

## 6. 发送 HTTP 请求

## 7. 服务器端处理 HTTP 请求流程

## 8. 浏览器解析报文，渲染出页面
