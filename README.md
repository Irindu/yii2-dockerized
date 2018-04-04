# yii2 dockerized

## setup

```
docker-compose build --build-arg WUID=$(id -u) --build-arg WGID=$(id -g) php
docker run --rm -v $PWD/app:/app local/yii2-dockerized rsync -avz vendor/ /app/vendor/
docker-compose up -d
```
