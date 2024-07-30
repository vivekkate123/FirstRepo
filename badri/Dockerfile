FROM openjdk:8-jdk-alpine

WORKDIR /app

COPY Hello.java .

RUN javac Hello.java 

CMD [ "java","Hello" ]


# For Spring-Boot project, use the entrypoint below to reduce Tomcat startup time.
#ENTRYPOINT exec java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar docker.jar
