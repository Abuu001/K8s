FROM openjdk:8-jre-alpine
MAINTAINER Abraham.Lugonzo
RUN mkdir /hello
COPY . /hello
#ADD dockertest-0.0.1.jar /hello/dockertest-0.0.1.jar
CMD ["java","-jar","/hello/dockertest-0.0.1.jar"]
#WORKDIR /hello
