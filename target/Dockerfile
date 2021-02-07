FROM openjdk:8

EXPOSE 8080/tcp

RUN mkdir app

COPY dropwizard-helloworld-1.0-SNAPSHOT.jar app
COPY hello-world.yml app
 
WORKDIR app

ENTRYPOINT ["java", "-jar", "-Done-jar.slient=true", "dropwizard-helloworld-1.0-SNAPSHOT.jar", "server", "hello-world.yml"]
