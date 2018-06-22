FROM java:8
VOLUME /tmp
ADD demo-0.0.1-SNAPSHOT.jar app.jar
ADD demo-0.0.1-SNAPSHOT.jar /app.jar
#RUN bash -c'touch/app.jar'
EXPOSE 8099
ENTRYPOINT ["java","-jar","/app.jar"]
#ENTRYPOINT ["java","-Djava.security.egd=/dev/urandom","/app.jar"]
