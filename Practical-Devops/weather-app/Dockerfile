
FROM openjdk:17-jdk-alpine


WORKDIR /app


COPY ./target/weather-app-0.0.1-SNAPSHOT.jar /app/weather-app.jar

RUN chmod +x /app/weather-app.jar

EXPOSE 8080


CMD ["java", "-jar", "weather-app.jar"]