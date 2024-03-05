FROM openjdk:8-jre-alpine

EXPOSE 8080

COPY /var/lib/jenkins/workspace/Final-project-Maven-*.jar /usr/app/java-maven-app.jar

WORKDIR /usr/app

CMD ["java", "-jar", "java-maven-app.jar"]
