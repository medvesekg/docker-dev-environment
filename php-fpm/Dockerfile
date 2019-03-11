FROM php:fpm

RUN apt-get update
RUN apt-get install libpng-dev -y

RUN docker-php-ext-install bcmath pdo_mysql gd