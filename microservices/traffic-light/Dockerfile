FROM ubuntu:latest
Label microservicehost="traffic-light"
RUN apt update
Run apt install nginx -y
RUN rm -rf /var/www/html/index.html
WORKDIR /var/www/html/
COPY traffic-light/* .
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]