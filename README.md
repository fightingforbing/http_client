# http_client
初看golang源码关于http client实现的时候， 里面用了很多的chan跟协程，看的一头雾水  
我们知道http 其实本质是TCP+符合http协议格式的数据流  
所以我们的目的是从最简单的TCP+HTTP协议的方式，一步步增加各种功能以及优化，循环渐进的实现golang源码的客户端，达到学习源码的目的
