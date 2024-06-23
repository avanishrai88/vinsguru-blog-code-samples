FROM openjdk:11.0.13-jre-slim

WORKDIR /usr/app

ADD target/*jar app.jar

CMD sleep 10 && java -jar app.jar