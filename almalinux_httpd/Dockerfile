FROM almalinux:minimal
RUN microdnf update -y && microdnf install httpd -y
COPY templatemo_559_zay_shop /var/www/html
EXPOSE 80
CMD ["httpd", "-D", "FOREGROUND"]
