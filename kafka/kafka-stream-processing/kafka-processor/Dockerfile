FROM openjdk:11.0.13-jre-slim

WORKDIR /usr/app

ADD target/kafka*.jar app.jar

ENTRYPOINT java -jar app.jar