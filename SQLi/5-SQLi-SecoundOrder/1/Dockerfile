#PHP Apache setup
FROM php:latest

#Update and install needed packages:
RUN apt-get update \
    && docker-php-ext-install mysqli \
    && docker-php-ext-enable mysqli
