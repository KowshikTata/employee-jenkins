FROM openjdk:8-jdk-alpine
EXPOSE 8081
ADD target/*.jar app.jar
ENTRYPOINT ["sh","-c","java -jar /app.jar"]