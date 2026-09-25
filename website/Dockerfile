 #Use official PHP image with Apache web server
FROM php:7.4-apache

# Set working directory inside the container
WORKDIR /var/www/html

# Copy the contents of the website directory into Apache's web root
COPY website/ /var/www/html/

# Expose HTTP port 80
EXPOSE 80
