FROM debian:stretch
LABEL maintainer="Hashtalt Developers <dev@hashtalt.org>"
LABEL description="Dockerised HashtaltCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
