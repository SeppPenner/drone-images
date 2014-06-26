FROM ubuntu:12.04
MAINTAINER Orne Brocaar <info@brocaar.com>

# update apt
RUN apt-get update
RUN apt-get upgrade -y

# install build essentials
RUN apt-get install -y build-essential

# install tools required by drone
RUN apt-get install -y git

# install python and pip
RUN apt-get install -y python-dev
RUN apt-get install -y python-pip
