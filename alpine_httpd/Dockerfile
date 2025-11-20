FROM alpine:latest
RUN apk update && apk add apache2
COPY iPortfolio-1.0.0 /var/www/html
EXPOSE 80
CMD ["httpd", "-D", "FOREGROUND"]
