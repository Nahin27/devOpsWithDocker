FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN apt-get -y update

RUN apt-get -y install curl

COPY web.sh .

RUN chmod +x web.sh

CMD ./web.sh


