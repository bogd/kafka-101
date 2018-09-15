FROM ubuntu:16.04

RUN apt update && apt install -y openjdk-8-jre

COPY kafka ./

CMD ./kafka/bin/kafka

