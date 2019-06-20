FROM debian:8
COPY apt_sources.list /etc/apt/sources.list
RUN dpkg --add-architecture i386
RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y eagle:i386
