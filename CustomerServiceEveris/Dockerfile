FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]

#FROM adoptopenjdk/openjdk8:alpine
#WORKDIR /opt
#COPY  target/docker-spring-boot.jar /opt
#ENTRYPOINT ["java","-jar","docker-spring-boot.jar"]