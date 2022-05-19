FROM openjdk:11
ADD target/*.jar pocdeployment-2.0.1-SNAPSHOT.jar 
ENTRYPOINT ["java", "-jar","pocdeployment-2.0.1-SNAPSHOT.jar"]
EXPOSE 8080