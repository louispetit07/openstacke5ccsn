FROM php:7.4-apache

# Copier le code source dans le répertoire web d'Apache
COPY src/ /var/www/html/

# Installer l'extension mysqli pour permettre la connexion à MySQL
RUN docker-php-ext-install mysqli

# Exposer le port 80
EXPOSE 80
