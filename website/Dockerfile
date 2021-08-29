FROM php:7.0-apache  
RUN rm /var/www/html/*
WORKDIR /opt/workspace/edurekaproject1_Job3/website/
COPY . /var/www/html
ENTRYPOINT service apache2 start && /bin/bash
