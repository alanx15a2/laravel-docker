FROM php:fpm
RUN docker-php-ext-install opcache \
    && docker-php-ext-install pdo_mysql
COPY --chown=www-data:www-data app/ /var/www/html
COPY php-ini/opcache.ini /usr/local/etc/php/conf.d/opcache.ini