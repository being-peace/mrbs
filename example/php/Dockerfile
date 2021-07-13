FROM php:7.3-apache

RUN a2enmod rewrite
RUN docker-php-ext-install mysqli

#COPY example/php.ini/ $PHP_INI_DIR/conf.d/
RUN docker-php-ext-install mysqli pdo pdo_mysql 
