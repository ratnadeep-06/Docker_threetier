FROM ubuntu:latest
Label microservicehost="todo"
RUN apt update
Run apt install nginx -y
RUN rm -rf /var/www/html/index.html
WORKDIR /var/www/html/
COPY todo6/* .
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]