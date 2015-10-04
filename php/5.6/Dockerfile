FROM php:5.6-cli

RUN apt-get update && apt-get -y upgrade

RUN apt-get install -y git

RUN docker-php-ext-install bcmath mbstring

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer