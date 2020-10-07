# 環境
![python-3.8-alpine](https://img.shields.io/badge/python-3.8--alpine-informational)
![ruby-2.7](https://img.shields.io/badge/ruby-2.7-red)
![docker-compose-3.4](https://img.shields.io/badge/docker--compose-3.4-blue)

# 前提条件

[docker](https://www.docker.com/)が導入済みであること

# 利用方法

build
```
docker-compose build --no-cache
```

up
```
docker-compose up -d
```

stop
```
docker-compose stop
```


delete
```
docker-compose down --rmi all
```