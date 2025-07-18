# Laravel Docker Examples Project
```
docker system prune --all --volumes --force

docker compose -f compose.prod.yaml up -d
docker compose -f compose.prod.yaml exec php-fpm php artisan key:generate

docker exec -it laravel-docker-examples-php-cli-1 php artisan route:

$ git fetch origin

$ git reset --hard origin/main

➜ docker inspect containerid | grep -i com.docker.compose.project (checking which file used)

docker image inspect Image --format '{{.Architecture}}' (check image archi)

```