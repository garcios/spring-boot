FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD /maven/spring-boot-1.0.jar spring-boot-1.0.jar
ENV JAVA_OPTS=""
ENTRYPOINT ["sh" ,"-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom  -jar /spring-boot-1.0.jar"]
LABEL maintainer "Oscar Garcia"