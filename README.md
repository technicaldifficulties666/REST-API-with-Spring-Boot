# REST-API-with-Spring-Boot README
## Overview
REST API with Spring Boot, utilizing Spring Security to authenticate and authorize the app. 


## Getting Started

NOTE: This guide assumes windows installation

To get started, you'll need to have  Java JDK version 17 and Gradle 8.6 installed on your machine 

Follow this guide to install and switch between multiple JDKs in windows: https://www.happycoders.eu/java/how-to-switch-multiple-java-versions-windows/ 

Follow guide on https://spring.io/quickstart for starting a new Spring Boot project

Optional: (if code doesn't compile)
add gradle.properties file in the project directory and add the line:
```bash
org.gradle.java.home =  C:/Program Files/Java/jdk-17 ##<Path to the JDK you want to use for your project (JDK 17)>
```

For building and running tests: In the terminal, go to project directory and run command
```bash 
./gradlew test
```
