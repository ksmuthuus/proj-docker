FROM ubuntu:latest

MAINTAINER Muthu Venkatachalam "ksmuthuus@yahoo.com"

RUN apt-get update && apt-get install -y openjdk-8-jdk

WORKDIR /usr/local/bin/

COPY test-program.jar .

CMD ["/bin/bash"]