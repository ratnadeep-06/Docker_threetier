FROM ubuntu:latest
Label microservicehost="counter"
RUN apt update
Run apt install nginx -y
RUN rm -rf /var/www/html/index.html
WORKDIR /var/www/html/
COPY counter/* .
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]