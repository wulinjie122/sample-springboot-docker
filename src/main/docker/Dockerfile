# this is my spring-boot docker sample

FROM frolvlad/alpine-oraclejdk8:slim
MAINTAINER wulinjie
VOLUME /tmp
ADD sample-springboot-docker-1.0-SNAPSHOT.jar app.jar
RUN sh -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
LABEL version="1.0"