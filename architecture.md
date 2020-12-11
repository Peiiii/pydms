微服务架构
---
### 参考
- [手把手教你搭建一个微服务docker+consul+kong](https://zhuanlan.zhihu.com/p/166614226)
### 微服务网关 Api gateway
Kong

### 服务注册与服务发现
Consul
- 服务自动注册： Registrator

### 微服务配置中心
pydms-config-server(开发中)

### 微服务消息总线
kafka?rabbit mq?

### 微服务日志收集
ELK(ElasticSearch + Logstash + Kibana)

### 微服务链路追踪和故障快速排查
Zipkin/OpenTracing

### 微服务之间调用机制
rest,thrift,gRPC,基于http自定义,基于TCP自定义,基于消息队列



---

### 具体服务功能
python/java/go
微服务可以被其它微服务调用
可以被客户端调用
可以被Api gateway调用

### 服务通信机制/IPC机制
REST/TCP/gRPC/消息队列RabbitMQ

### 文档数据库
Mogodb

### 缓存数据库
redis

###其它
mysql

### 搜索服务
ElasticSearch

### 日志与监控

待定


### 负载均衡和反向代理
nginx