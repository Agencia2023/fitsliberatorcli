FROM ubuntu:20.04

WORKDIR /src
COPY . ../../fits-liberator-cli/
 
RUN apt-get update
RUN apt -y install nodejs
RUN apt-get install -y build-essential
RUN apt install -y libcfitsio-dev libtiff-dev libvips-dev