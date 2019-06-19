FROM ubuntu:16.04

RUN apt-get update && apt-get -y install curl

WORKDIR /

COPY script .

RUN chmod u+x script

CMD ["./script"]
