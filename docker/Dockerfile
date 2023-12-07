# image 
FROM php:8.1-apache 

# installateur d'extensions PHP
ADD https://github.com/mlocati/docker-php-extension-installer/releases/latest/download/install-php-extensions /usr/local/bin/
# permissions nécessaires à l'installateur
RUN chmod +x /usr/local/bin/install-php-extensions && \
     install-php-extensions pdo_mysql intl

