FROM ubuntu:22.04
RUN apt update -y && apt install apache2 -y
COPY 2100_artist /var/www/html
EXPOSE 80
CMD ["apache2ctl", "-D", "FOREGROUND"]
