FROM ubuntu:16.04

LABEL maintainer="Bogdan Sass"

RUN apt update && apt -y install zookeeperd

EXPOSE 2181/tcp
EXPOSE 3181/tcp

ENTRYPOINT [ "zookeeperd" ]
CMD [ "" ]
