
FROM java:8

EXPOSE 5003

ADD target/docker-abc-user-management.jar docker-abc-user-management.jar

ENTRYPOINT ["java","-jar","docker-abc-user-management.jar"]