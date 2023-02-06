FROM openjdk:14-jdk-alpine

EXPOSE 8080

WORKDIR /app

COPY ./target/asset-assignment-0.0.1-SNAPSHOT.jar webapp.jar

CMD ["java", "-jar", "webapp.jar"]
