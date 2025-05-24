# Use a base image with Java installed
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/personalfinancetracker-0.0.1-SNAPSHOT.jar /app/personalfinancetracker-0.0.1-SNAPSHOT.jar

# Expose the port that the Spring Boot application will run on
EXPOSE 8081

# Specify the command to run the application when the container starts
CMD ["java", "-jar", "personalfinancetracker-0.0.1-SNAPSHOT.jar"]