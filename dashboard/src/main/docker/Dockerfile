FROM java:7
VOLUME /tmp
ADD dashboard-0.0.1-SNAPSHOT.jar /app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 8989
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]docker