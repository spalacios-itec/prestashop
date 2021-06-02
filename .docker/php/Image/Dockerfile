FROM php:7.3-fpm-alpine

RUN apk update
RUN apk add curl-dev libxml2-dev libpng-dev icu-dev libzip-dev

RUN docker-php-ext-install pdo_mysql curl dom fileinfo gd iconv intl json mbstring pdo simplexml zip

CMD ["php-fpm"]

EXPOSE 9000