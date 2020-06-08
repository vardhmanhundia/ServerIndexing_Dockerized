FROM adoptopenjdk/openjdk14
VOLUME /tmp
ADD target/serverindex-2.3.0.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]