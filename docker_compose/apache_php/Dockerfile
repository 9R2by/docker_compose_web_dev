#https://github.com/docker-library/php/blob/1bc63c1ce4294a4ecb50c60dcf6a57d6749cba7d/7.4/buster/apache/Dockerfile
FROM php:7.4-apache

RUN apt update && apt upgrade -y

RUN docker-php-ext-install mysqli pdo_mysql

# Use development configuration
RUN mv "$PHP_INI_DIR/php.ini-development" "$PHP_INI_DIR/php.ini"

#https://hub.docker.com/_/php