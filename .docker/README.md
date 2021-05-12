# Dockerized PHP OpenID Connect Basic Client

## Install
1. copy `.docker/sample.env` to `.docker/.env` and set 
1. copy `.docker/images/php/php.sample.ini` to `.docker/images/php/php.ini` and set 
1. `docker-compose build`
1. `docker-compose run --rm php composer install`

## Tests
1. `docker-compose run --rm php vendor/bin/phpunit tests`
