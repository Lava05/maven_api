FROM openjdk:17
WORKDIR /app
EXPOSE 8080
COPY target/docker-0.0.1-SNAPSHOT.jar app.jar
CMD ["java","-jar","app.jar"]