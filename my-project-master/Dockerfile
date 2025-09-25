FROM openjdk:8-jre-alpine
WORKDIR /usr/app
EXPOSE 8080

COPY ./build/libs/*.jar /usr/app/app.jar

WORKDIR /usr/app

ENTRYPOINT ["java","-jar","/usr/app/app.jar"]
