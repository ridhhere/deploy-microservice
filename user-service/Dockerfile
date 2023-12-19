FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /app/user-service.jar
ENTRYPOINT ["java","-jar","/app/user-service.jar"]
EXPOSE 9002
