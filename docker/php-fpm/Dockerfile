FROM php:7.2-fpm-alpine

WORKDIR "/app"

RUN docker-php-ext-install -j$(nproc) mysqli pdo_mysql
