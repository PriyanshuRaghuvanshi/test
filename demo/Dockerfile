# Use a base image with Java 17
FROM adoptopenjdk:17-jre

# Set the working directory in the container
WORKDIR /app

# Copy the built JAR file into the container
COPY target/demo-0.0.1-SNAPSHOT.jar ./demo-0.0.1-SNAPSHOT.jar

# Specify the command to run on container startup
CMD ["java", "-jar", "demo-0.0.1-SNAPSHOT.jar"]
