FROM eclipse-temurin:17-jdk-alpine
LABEL maintainer=448417@qq.com

COPY target/*.jar /app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/app.jar"]