FROM eclipse-temurin:17-jre

WORKDIR /app

COPY target/gs-maven-0.1.0.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]
