FROM php:5.6-apache

RUN docker-php-ext-install pdo_mysql && \
    docker-php-ext-install mysql && \
    a2enmod rewrite