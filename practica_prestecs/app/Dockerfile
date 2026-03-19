# 1. Partimos de PHP con Apache
FROM php:8.2-apache

# 2. Instalamos la extensión mysqli (necesaria para conectar con MariaDB)
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

# 3. Carpeta del servidor web
WORKDIR /var/www/html