# Bitwarden

## 1、创建网络

```SHELL
docker network create bitwarden
```

## 2、启动

```SHELL
export VAULTWARDEN_DATA_PATH="/opt/data/vaultwarden"
docker-compose up -d
```

## 3、访问

http://localhost:8080
