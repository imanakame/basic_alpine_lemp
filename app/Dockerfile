FROM php:7.4.1-fpm-alpine

RUN docker-php-ext-install pdo_mysql mysqli && \
apk --update add tzdata
ENV TZ=Asia/Tokyo