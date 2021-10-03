FROM adoptopenjdk/openjdk15:ubi
ADD build/libs/spring-boot-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
CMD ["java", "-jar", "app.jar"]
