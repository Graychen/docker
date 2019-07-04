FROM zacksleo/php:laravel-dev
WORKDIR /var/www/html
COPY . /var/www/html
RUN apk add libressl-dev
RUN pecl install mongodb \
    && pecl clear-cache
RUN echo "extension=mongodb.so" > /usr/local/etc/php/conf.d/docker-php-ext-mongodb.ini
VOLUME ["/var/www/html"]