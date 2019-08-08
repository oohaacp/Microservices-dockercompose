FROM openjdk:11-jre
WORKDIR /usr/src
ADD ./target/config-services-0.0.1-SNAPSHOT.jar  /usr/src/config-services-0.0.1-SNAPSHOT.jar
EXPOSE 8888
ENTRYPOINT ["java","-jar","/usr/src/config-services-0.0.1-SNAPSHOT.jar"]



