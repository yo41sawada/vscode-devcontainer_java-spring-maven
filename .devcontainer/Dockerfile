FROM openjdk:11.0.14.1-slim-bullseye

WORKDIR /opt
RUN apt update && apt install wget git -y
RUN wget https://dlcdn.apache.org/maven/maven-3/3.8.5/binaries/apache-maven-3.8.5-bin.tar.gz
RUN tar -zxvf apache-maven-3.8.5-bin.tar.gz
RUN echo 'export PATH="$PATH:/opt/apache-maven-3.8.5/bin"' > /root/.profile