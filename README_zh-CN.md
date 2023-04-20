# 环境依赖
- docker compose >= 1.29.2, docker >= 20.10

# 配置
打开`.env`文件，根据实际情况修改配置。
- `SERVER_HOST_DNS`: 服务使用的`DNS`，请改成服务器网卡的IP地址。
- `SERVER_HOST_PORT`: 服务使用的端口号，请分配一个未被使用的端口号。
- `MYSQL_ROOT_PASSWORD`: 数据库`root`用户的密码。
- `MYSQL_INITIAL_USER`: 数据库初始用户名。
- `MYSQL_INITIAL_PASSWORD`: 数据库初始用户的密码。

# 安装运行
```
docker-compose up -d
```