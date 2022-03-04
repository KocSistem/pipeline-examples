FROM adoptopenjdk/openjdk11:jdk-11.0.9.1_1
VOLUME /tmp
COPY target/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]