FROM php:7.4-apache
RUN pecl install redis \
    && pecl install xdebug \
    && docker-php-ext-enable redis xdebug
COPY xdebug.ini /usr/local/etc/php/conf.d/
