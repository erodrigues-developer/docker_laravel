**This environment was based on: https://www.digitalocean.com/community/tutorials/how-to-set-up-laravel-nginx-and-mysql-with-docker-compose**


## Start
**Run this script for initialize your APP**
```shell
docker-compose up -d
```

## Migration

**Run this script for migrate your DB**
```shell
docker-compose exec app php artisan migrate
```
