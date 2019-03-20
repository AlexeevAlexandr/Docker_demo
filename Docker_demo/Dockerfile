FROM ubuntu:latest
MAINTAINER Alexandr Alexeev <alexandralexeevkiev@gmail.com>
RUN \apt-get update -y && \apt-get install default-jre -y
ADD ./target/Docker_demo-1.0-SNAPSHOT.jar spring-mvc-example.jar
EXPOSE 8080
CMD java -jar spring-mvc-example.jar
