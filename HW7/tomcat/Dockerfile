FROM tomcat:8-jre8-slim
RUN apt-get update
COPY --from=hw7_mav:latest /boxfuse-sample-java-war-hello/target/hello-1.0.war /usr/local/tomcat/webapps/
CMD ["catalina.sh", "run"]
