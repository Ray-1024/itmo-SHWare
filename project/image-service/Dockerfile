FROM openjdk:21-jdk-slim
LABEL authors="Ray_1024"
WORKDIR /app
COPY target/image-service-0.0.1-SNAPSHOT.jar /app/app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
