FROM openjdk:21-jdk-alpine
VOLUME /tmp
ADD my-site-1.0.2.RELEASE.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]