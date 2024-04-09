FROM php:8.2-alpine3.19

COPY docker/config/php/opcache.ini /usr/local/etc/php/conf.d/opcache.ini

WORKDIR /app
COPY . .

ENTRYPOINT [ "php" ]
CMD [ "-S", "0.0.0.0:8080" ]
