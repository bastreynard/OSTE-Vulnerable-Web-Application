FROM php:fpm-alpine
RUN docker-php-ext-install mysqli pdo pdo_mysql
COPY ./oste-site/ /var/www/html/
RUN mv "$PHP_INI_DIR/php.ini-development" "$PHP_INI_DIR/php.ini"