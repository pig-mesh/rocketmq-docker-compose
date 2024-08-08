## 如何使用

```
git clone https://github.com/pig-mesh/rocketmq-docker-compose.git

cd rocketmq-docker-compose

vim broker.conf
```

## 配置 broker.conf

![](https://minio.pigx.top/oss/202308/1691420812.png)

```
# 通过此命令查看宿主机IP
docker network inspect bridge
```

## 启动服务

```
docker compose up -d
```
