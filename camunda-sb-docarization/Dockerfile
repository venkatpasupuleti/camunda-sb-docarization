FROM camunda/camunda-bpm-platform
COPY ./target/camunda-sb-docarization.jar /usr/local/tomcat/webapps/camunda-sb-docarization.jar 
ENTRYPOINT ["java", "-jar", "/usr/local/tomcat/webapps/camunda-sb-docarization.jar"]