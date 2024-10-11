FROM openjdk:11-jre-slim
WORKDIR /app

COPY target/dependency/webapp-runner.jar /app

EXPOSE 8080

CMD ["java", "-jar", "webapp-runner.jar"]
