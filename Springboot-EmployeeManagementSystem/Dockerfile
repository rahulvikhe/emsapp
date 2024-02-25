FROM openjdk:17

# Set the working directory
WORKDIR /app

# Copy the Spring Boot application JAR file into the image
COPY /target/EmployeeManagementSystem-0.0.1-SNAPSHOT.jar /app/EmployeeManagementSystem-0.0.1-SNAPSHOT.jar

# Expose the port that the Spring Boot application will run on
EXPOSE 8082

# Specify the command to run the Spring Boot application
ENTRYPOINT ["java", "-jar", "EmployeeManagementSystem-0.0.1-SNAPSHOT.jar"]
