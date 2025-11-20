FROM alpine:latest
RUN apk update && apk add nginx 
COPY fitness-website-template /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
