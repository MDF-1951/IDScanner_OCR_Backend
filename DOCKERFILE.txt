FROM eclipse-temurin:21-jdk
WORKDIR /app
COPY target/app.jar app.jar
EXPOSE 10000
CMD ["java","-jar","app.jar"]
