微服务框架中的各个模块
---
### 启动顺序
consul->kong->registrator

### 启动前准备
```shell script
# 建立网络
docker network create mirco
```

- consul
```shell script
cd consul
# start
docker-compose up -d
# stop
docker-compose down
```
GUI端口 8500,8501
- kong
```shell script
cd kong
# start
docker-compose up -d
# stop
docker-compose down
```
konga端口 1337
