FROM useoff/ubuntu-build-essential:latest 

MAINTAINER Plutod Useoff <plutod.useoff@gmail.com> 

RUN apt-get update && apt-get install -y software-properties-common \
	&& apt-add-repository -y ppa:beineri/opt-qt59-xenial

RUN apt-get update && apt-get install -y \
		libgl1-mesa-dev \
		qt59base \
		qt59declarative \
		qt59tools \
		qt59translations \
		qt59quickcontrols \
		qt59quickcontrols2 \
	&& rm -rf /var/lib/apt/lists/*

ENV PATH /opt/qt59/bin:$PATH
