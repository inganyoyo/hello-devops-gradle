FROM openjdk:18.0.2.1-jdk-oraclelinux8
COPY hello-springboot/build/libs/*.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/app.jar"]
