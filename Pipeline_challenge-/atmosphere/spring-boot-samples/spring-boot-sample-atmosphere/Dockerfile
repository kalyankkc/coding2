FROM openjdk:8
RUN mkdir -p /usr/src/myapp

COPY target/spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar   /usr/src/myapp

# Setup Working DIR
WORKDIR /usr/src/myapp

#EXPOSE
EXPOSE 8080

# Start the Bot Service
CMD ["java", "-jar", "jar_file"]
