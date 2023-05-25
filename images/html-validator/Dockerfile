FROM python:3.8-buster

RUN apt-get -y update && apt-get -y install curl

RUN pip3 install html5validator
RUN wget https://github.com/validator/validator/releases/download/20.6.30/vnu.linux.zip
RUN unzip vnu.linux.zip
