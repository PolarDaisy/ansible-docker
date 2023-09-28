FROM php:7.4-fpm-alpine

RUN apk add --no-cache \
        nginx

COPY . /var/www/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]