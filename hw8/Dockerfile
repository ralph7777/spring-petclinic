FROM openjdk:8u191-jre-alpine
MAINTAINER Kuangyi Zhang
COPY target/spring-petclinic-2.1.0.BUILD-SNAPSHOT.jar spring-petclinic.jar
ENTRYPOINT ["java","-jar","spring-petclinic.jar"]
EXPOSE 8080