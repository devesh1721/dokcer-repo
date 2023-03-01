FROM openjdk:8
WORKDIR /usr
ADD target/BookService-0.0.1-SNAPSHOT.jar /usr
EXPOSE 9090

ENTRYPOINT ["java", "-jar", "/BookService-0.0.1-SNAPSHOT.jar"]