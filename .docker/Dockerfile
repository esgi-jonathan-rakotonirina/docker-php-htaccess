FROM php:5.6-apache

MAINTAINER Louis HARANG <lharang.pro@gmail.com>

RUN apt-get update \
 && docker-php-ext-install pdo pdo_mysql

RUN a2enmod rewrite

WORKDIR /var/www
