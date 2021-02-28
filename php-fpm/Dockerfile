FROM php:fpm
RUN docker-php-ext-install opcache
COPY --chown=www-data:www-data app/ /var/www/html