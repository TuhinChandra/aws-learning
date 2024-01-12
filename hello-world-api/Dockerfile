FROM bellsoft/liberica-openjdk-alpine:17
COPY build/libs/hello-world-api-0.0.1-SNAPSHOT.jar helloworld-api.jar
EXPOSE 8080
ENTRYPOINT exec java $JAVA_OPTS -jar helloworld-api.jar
