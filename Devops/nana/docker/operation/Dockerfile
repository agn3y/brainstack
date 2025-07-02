FROM openjdk:11

EXPOSE 8080

WORKDIR /usr/app
COPY target/java-maven-app-1.1.0-SNAPSHOT.jar /usr/app

ENTRYPOINT ["java","-jre","java-maven-app-1.1.0-SNAPSHOT.jar"]
