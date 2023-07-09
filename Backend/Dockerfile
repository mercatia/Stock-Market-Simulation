FROM eclipse-temurin:17
WORKDIR /app
ADD target/*.jar app.jar
ENTRYPOINT ["java","-jar","app.jar", "--spring.config.name=application-docker"]