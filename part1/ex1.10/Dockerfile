FROM ubuntu:16.04

WORKDIR /
COPY frontend-example-docker .
EXPOSE 5000

RUN apt-get update && apt-get upgrade -y
RUN apt-get install curl -y
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
RUN npm install


CMD npm start
