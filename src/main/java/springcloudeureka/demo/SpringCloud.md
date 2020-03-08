Spring Cloud
    Spring Cloud封装了Netflix公司开发的Eureka模块来实现服务注册和发现，Eureka采用了C-S的设计架构，
Eureka Server作为服务注册功能的服务器，它是服务注册中心，而系统中的其他微服务，使用Eureka的客户端连接到
Eureka Server，并维持心跳连接。这样系统的维护人员就可以通过Eureka Server来监控系统中各个微服务是否正常运行。

  Eureka由两个组件组成：Eureka服务器和Eureka客户端，Eureka服务器作为服务注册服务器，Eureka客户端是一个Java
客户端，用来简化与服务器的交互，作为轮询负载均衡器，并提供服务的故障支持。





