# README

## Install Laravel Application Template

```
$ docker-compse exec laravel-php laravel new application
```

## Nginx

1. nginx/default.conf

```
root /src/application/public;
```

1. nginx restart

```
$ docker-compose exec nginx restart;
```
