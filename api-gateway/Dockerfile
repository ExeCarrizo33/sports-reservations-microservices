FROM eclipse-temurin:17.0.13_11-jdk

VOLUME /tmp

COPY target/api-gateway-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java","-jar","/app.jar"]

EXPOSE 8761
