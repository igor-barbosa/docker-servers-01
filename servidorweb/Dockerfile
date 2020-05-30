FROM php:7.3-apache

RUN apt-get update &&  apt-get install -y \
     #dependências do php-zip 
     zlib1g-dev \
     libzip-dev \
     #dependências do GD
     libpng-dev

RUN docker-php-ext-install mbstring pdo pdo_mysql mysqli

RUN docker-php-ext-install zip

RUN docker-php-ext-install gd
