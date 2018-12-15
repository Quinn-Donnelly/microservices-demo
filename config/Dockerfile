FROM openjdk:8
COPY ./target/config-0.0.1-SNAPSHOT.jar /opt
WORKDIR /opt
EXPOSE 8761
CMD ["java", "-jar", "config-0.0.1-SNAPSHOT.jar"]
