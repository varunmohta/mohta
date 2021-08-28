FROM devopsedu/webapp  
RUN rm /var/www/html/*
WORKDIR /opt/workspace/edurekaproject1_docker/website/
COPY . /var/www/html
ENTRYPOINT service apache2 start && /bin/bash
