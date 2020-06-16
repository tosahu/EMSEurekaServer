FROM openjdk:latest
ADD /target/*.jar EmsEurekaServer.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","/EmsEurekaServer.jar"]