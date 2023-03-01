FROM ubuntu:20.04

WORKDIR /app

RUN apt-get update

RUN apt-get install -y curl

COPY . .

RUN chmod +x web.sh

ENTRYPOINT [ "./web.sh" ]