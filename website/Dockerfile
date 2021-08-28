FROM devopsedu/webapp  
RUN rm /var/www/html/*
COPY /website/. /var/www/html
ENTRYPOINT service apache2 start && /bin/bash
