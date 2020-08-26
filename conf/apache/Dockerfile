FROM php:7.2-apache

RUN apt-get update \
   && docker-php-ext-install pdo pdo_mysql mysqli \
   && a2enmod rewrite

# install node js


# Install Composer
#RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer