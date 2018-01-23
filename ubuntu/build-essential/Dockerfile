FROM useoff/ubuntu-base:latest

MAINTAINER Plutod Useoff <plutod.useoff@gmail.com> 

RUN apt-get update && apt-get install \
		build-essential \
		cppcheck \
		valgrind \
		&& rm -rf /var/lib/apt/lists/*
