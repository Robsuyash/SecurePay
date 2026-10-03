#fraud-detection-service/Dockerfile


#Step 1 - Use java 17 as base image
FROM eclipse-temurin:17-jre-alpine

#Step 2 Set working directory inside container
WORKDIR /app

#Step 3 copy the built jar file
COPY target/fraud-detection-service-0.0.1-SNAPSHOT.jar app.jar

#Step 4 expose port
EXPOSE 8091

#Step 5 Run the jar
ENTRYPOINT ["java","-jar","app.jar"]
