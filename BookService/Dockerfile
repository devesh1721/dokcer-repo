FROM java:8-jdk
RUN mkdir /app
WORKDIR /app
COPY target/BookService-0.0.1-SNAPSHOT.jar /app
EXPOSE 9090

ENTRYPOINT ["java", "-jar", "user-service-0.0.1-SNAPSHOT.jar"]