FROM eclipse-temurin:17.0.13_11-jdk

WORKDIR /app

COPY target/config-server-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8888

ENTRYPOINT ["java", "-jar", "/app/app.jar"]
