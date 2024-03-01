FROM php:8.2-apache

WORKDIR /var/www
COPY . /var/www

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

ENV COMPOSER_ALLOW_SUPERUSER=1

RUN apt-get update
RUN apt-get install zip unzip
RUN apt-get install gzip tar

RUN composer update
RUN composer install

CMD ["apache2-foreground"]