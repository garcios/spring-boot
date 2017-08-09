FROM alpine-java:base
MAINTAINER garcios.space
COPY /maven/spring-boot-1.0.jar spring-boot-1.0.jar
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "spring-boot-1.0.jar"]
VOLUME /tmp
EXPOSE 8090