# yii2 dockerized

## setup

```
docker-compose build --build-arg WUID=$(id -u) --build-arg WGID=$(id -g) php
docker-compose up -d
```
