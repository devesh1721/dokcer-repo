FROM openjdk:8
RUN mkdir /app
WORKDIR /app
COPY target/BookService-0.0.1-SNAPSHOT.jar /app
EXPOSE 9090

ENTRYPOINT ["java", "-jar", "BookService-0.0.1-SNAPSHOT.jar"]