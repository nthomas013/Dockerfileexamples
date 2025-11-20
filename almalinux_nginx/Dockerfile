FROM almalinux:minimal
RUN microdnf update -y && microdnf install nginx -y
COPY 2100_artist /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
