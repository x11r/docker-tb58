FROM php:7.2-fpm-alpine3.8

# autoconf, build-case
#RUN apk upgrade \
#  && apk update

#RUN apk add --no-cache --update autoconf
#RUN apk add --no-cache --update build-base

RUN apk add autoconf build-base
RUN pecl install xdebug
RUN docker-php-ext-enable xdebug
RUN docker-php-ext-install pdo_mysql
