FROM ubuntu:18.04

RUN apt update -y; apt install nginx -y

EXPOSE 80

COPY index.nginx-debian.html /var/www/html/ 

CMD ["nginx", "-g", "daemon off;"]

