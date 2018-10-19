FROM java:8
EXPOSE 8081

VOLUME /tmp
ADD youth-api.jar /app.jar
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-jar","/app.jar"]
