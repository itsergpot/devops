FROM maven:3-jdk-8-slim AS buildstg
RUN apt-get update
RUN apt-get install -y git && git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
RUN cd /boxfuse-sample-java-war-hello && mvn package
