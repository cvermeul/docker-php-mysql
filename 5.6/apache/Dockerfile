FROM php:5.6-apache

RUN apt-get update && \
	docker-php-ext-install pdo pdo_mysql mysql && \
	a2enmod rewrite && a2enmod headers && a2enmod expires && \
	service apache2 restart
