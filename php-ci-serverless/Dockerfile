FROM php:8.2.10-cli-alpine
LABEL authors="Martin Schimmel"

RUN apk add composer nodejs npm aws-cli zip libzip-dev icu-dev

RUN docker-php-ext-install pdo_mysql zip bcmath intl

RUN npm install -g serverless

