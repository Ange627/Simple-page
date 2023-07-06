FROM php:8.0.26-apache
RUN docker-php-ext-install -j$(nproc) mysqli
COPY ./ /var/www/html/