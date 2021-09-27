FROM php:7.4-apache

RUN docker-php-ext-install mysqli pdo_mysql

# Use development configuration
RUN mv "$PHP_INI_DIR/php.ini-development" "$PHP_INI_DIR/php.ini"
