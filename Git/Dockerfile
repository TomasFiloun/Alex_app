# Use an official OpenJDK 17 runtime as a parent image
FROM openjdk:17

# Set the working directory in the container
WORKDIR /app

# Copy the .jar file into the container at /app
COPY ondra-docker-1.0.jar /app/ondra-docker-1.0.jar

# Command to run the application
CMD ["java", "-jar", "ondra-docker-1.0.jar"]