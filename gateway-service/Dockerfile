FROM openjdk:11
LABEL maintainer="kirtishkhandar"
ADD target/gateway-service-0.0.1-SNAPSHOT.jar gateway-service.jar
ENTRYPOINT ["java", "-jar", "gateway-service.jar"]