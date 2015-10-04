FROM php:7.0-cli

RUN apt-get update && apt-get -y upgrade

RUN apt-get install -y git

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer