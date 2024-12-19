# Use a base image with JRE installed
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file from the target directory into the container
COPY target/spring-boot-web.jar app.jar

# Expose the port your Spring Boot application listens on (default: 8080)
EXPOSE 8080

# Run the application
CMD ["java", "-jar", "app.jar"]
