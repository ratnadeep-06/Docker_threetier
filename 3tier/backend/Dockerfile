FROM ubuntu:latest
LABEL Backend="studentappbackend"
ADD  https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.93/bin/apache-tomcat-9.0.93.zip /opt
WORKDIR /opt/
RUN apt update && \
    apt install unzip openjdk-11-jdk -y && \
    unzip apache-tomcat-9.0.93.zip
    COPY 