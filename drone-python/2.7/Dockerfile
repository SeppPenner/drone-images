FROM ubuntu:12.04
MAINTAINER Orne Brocaar <info@brocaar.com>

ENV DEBIAN_FRONTEND noninteractive

# update apt
RUN apt-get update
RUN apt-get upgrade -y

# install en language pack
RUN apt-get install -y language-pack-en

# install build essentials
RUN apt-get install -y build-essential

# install tools required by drone
RUN apt-get install -y git

# install python and pip
RUN apt-get install -y python-dev
RUN apt-get install -y python-pip

# Update pip and setuptools
RUN pip install setuptools -U
RUN pip install pip -U
RUN pip install wheel

# Install some common used libraries
RUN apt-get install -y libmysqlclient-dev
RUN apt-get install -y libxslt1-dev
