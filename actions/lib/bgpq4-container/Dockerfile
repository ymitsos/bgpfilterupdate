FROM ubuntu:20.10

LABEL version="0.1"
ARG TODAY=$(date +%F)
ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get -qqy update
RUN apt-get -qqy install bgpq4 iputils-ping
RUN rm -rf /var/cache/apt

#VOLUME ["/data"]
STOPSIGNAL SIGINT
