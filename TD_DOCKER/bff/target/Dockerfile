FROM openjdk:11-jre-slim

WORKDIR /app

COPY bff-0.0.1-SNAPSHOT.jar /app/bff.jar
COPY application-docker.properties /app/application.properties

CMD ["java", "-jar", "bff.jar"]
