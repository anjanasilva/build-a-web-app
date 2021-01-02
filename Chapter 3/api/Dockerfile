FROM php:7.3-apache 

RUN apt-get update && apt-get install -y libzip-dev libjpeg62-turbo-dev libpng-dev libfreetype6-dev
RUN docker-php-ext-install pdo_mysql mbstring zip exif pcntl gd