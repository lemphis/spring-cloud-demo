FROM gradle:jdk17

COPY ./ ./

RUN ["./gradlew", "clean", "build"]

ENTRYPOINT ["java", "-jar", "./build/libs/eureka-server.jar"]