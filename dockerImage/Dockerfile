FROM php:7.4-apache
LABEL "Author" = "Aadarsha"
LABEL "Project" = "Apache2"
ENV DEBIAN_FRONTEND=noninteractive
RUN apt update 
RUN apt install git -y
RUN apt install apache2 -y
RUN git clone https://github.com/silarhi/php-hello-world.git /var/www/html
EXPOSE 80
CMD ["apache2-foreground"]
