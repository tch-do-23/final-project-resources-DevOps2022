FROM openjdk:8-jre-alpine

EXPOSE 8080

COPY /home/ec2-user/ansible_DevOps2022/final-project-resources-DevOps2022/java-maven-app/target/java-maven-app-*.jar /usr/app/java-maven-app.jar
WORKDIR /usr/app

CMD java -jar java-maven-app-*.jar
