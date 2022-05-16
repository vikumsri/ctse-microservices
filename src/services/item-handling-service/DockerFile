FROM java:8

EXPOSE 5003

ADD target/docker-abc-item-service.jar docker-abc-item-service.jar

ENTRYPOINT ["java","-jar","docker-abc-item-service.jar"]