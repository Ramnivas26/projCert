FROM devopsedu/webapp
LABEL name=Sandhiya
RUN apt-get update -y
RUN rm /var/www/html/index.html
COPY / /var/www/html/
ENTRYPOINT service apache2 start && bash
