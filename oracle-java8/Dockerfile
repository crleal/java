#
# Oracle Java 8 Dockerfile
#
# https://github.com/dockerfile/java
# https://github.com/dockerfile/java/tree/master/oracle-java8
#

# Pull base image.
FROM ubuntu:latest

# Install Java.

RUN apt-get update && apt-get dist-upgrade -y && \
	apt-get autoclean && apt-get --purge -y autoremove && \
	rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
	

