FROM php:8.1-apache
WORKDIR /var/www/html
RUN docker-php-ext-install mysqli 

RUN chown -R www-data:www-data /var/www/html \
    && chmod -R o-wx /var/www/html
