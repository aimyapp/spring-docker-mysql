FROM ubuntu:20.10

RUN apt-get update
RUN apt-get -y install openjdk-16-jdk
ENV JAVA_HOME /usr/lib/jvm/java-16-openjdk-amd64
ENV PATH $JAVA_HOME/bin:$PATH
VOLUME /tmp
RUN mkdir /app
WORKDIR /app