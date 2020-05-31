FROM php:7.3.0-apache

# Install Composer

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

RUN docker-php-ext-install \
    pdo_mysql \
    && a2enmod \
    rewrite \