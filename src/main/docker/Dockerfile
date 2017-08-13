FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD /maven/eureka-service-1.0.jar eureka-service-1.0.jar
ENV JAVA_OPTS=""
ENTRYPOINT ["sh" ,"-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom  -jar /eureka-service-1.0.jar"]
LABEL maintainer "Oscar Garcia"