FROM eclipse-temurin:17-jre-jammy
WORKDIR /app
COPY target/service-a-1.0.0.jar app.jar
EXPOSE 8080
CMD ["java", "-jar", "app.jar"]
