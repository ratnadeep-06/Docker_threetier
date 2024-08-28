FROM ubuntu:latest
LABEL SITEHOST="TODO"
RUN apt update
RUN apt install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
WORKDIR /usr/share/nginx/html/
COPY todo6/* .
EXPOSE 80
CMD ["nginx", "-gdaemon off;"]