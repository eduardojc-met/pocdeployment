FROM openjdk:11
ADD target/*.jar pocdeployment.jar 
ENTRYPOINT ["java", "-jar","pocdeployment.jar"]
EXPOSE 8080