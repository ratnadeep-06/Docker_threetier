FROM ubuntu:latest
Label microservicehost="season-switcher"
RUN apt update
Run apt install nginx -y
RUN rm -rf /var/www/html/index.html
WORKDIR /var/www/html/
COPY season-switcher/* .
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]