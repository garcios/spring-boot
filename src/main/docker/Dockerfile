FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD /maven/spring-boot-1.0.jar spring-boot-1.0.jar
RUN sh -c 'touch /spring-boot-1.0.jar'
EXPOSE 8090
ENV JAVA_OPTS=""
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-Dapp.port=${app.port}", "-jar","/spring-boot-1.0.jar"]
LABEL maintainer "Oscar Garcia"