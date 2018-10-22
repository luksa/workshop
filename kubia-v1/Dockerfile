FROM java:8
COPY target/*.jar /opt/kubia/
EXPOSE 8080
ENTRYPOINT ["java", "-cp", "/opt/kubia/*", "com.example.kubia.App"]
