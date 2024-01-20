# Use OpenJDK 11 as the base image
FROM openjdk:11

# Set the working directory inside the container
WORKDIR /app

RUN pwd
 
# Copy the JAR file into the container at /app
COPY learn.jar /app/

# Expose the port that the application will run on (if applicable)
# EXPOSE 8080

# Specify the default command to run on container startup
ENTRYPOINT ["java", "-jar", "learn.jar"]

