FROM php:fpm
RUN docker-php-ext-install opcache \
    && docker-php-ext-install pdo_mysql
COPY --chown=www-data:www-data app/ /var/www/html