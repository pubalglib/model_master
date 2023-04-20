# Environment dependencies
- docker compose >= 1.29.2, docker >= 20.10

# Configuration
Edit the `.env` file base on your environment.
- `SERVER_HOST_DNS`: The `DNS` used by the server, please set the IP to the server's external IP address.
- `SERVER_HOST_PORT`: The `port` used by the server, please set it to a port number that is not in use.
- `MYSQL_ROOT_PASSWORD`: The password of database's `root` user.
- `MYSQL_INITIAL_USER`: The initial user name of the database.
- `MYSQL_INITIAL_PASSWORD`: The password of the database's initial user.

# Installation
```
docker-compose up -d
```