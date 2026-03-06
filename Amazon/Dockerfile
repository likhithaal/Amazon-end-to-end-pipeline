# Dockerfile for WAR file deployment
FROM tomcat:9-jdk11
RUN rm -rf /usr/local/tomcat/webapps/*
COPY Amazon-Web/target/*.war /usr/local/tomcat/webapps/Amazon.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
