FROM openjdk:11-jre
WORKDIR /usr/src
ADD ./target/zuul-gateway-0.0.1-SNAPSHOT.jar /usr/src/zuul-gateway-0.0.1-SNAPSHOT.jar
EXPOSE 8092
ENTRYPOINT ["java","-jar","/usr/src/zuul-gateway-0.0.1-SNAPSHOT.jar"]

