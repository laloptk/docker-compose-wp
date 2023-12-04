# Use the official Apache image as the base
FROM php:${PHP_VERSION:-7.4}-apache

# Enable required Apache modules
RUN a2enmod rewrite

# Copy the Apache configuration file
COPY default.conf /etc/apache2/sites-available/000-default.conf
