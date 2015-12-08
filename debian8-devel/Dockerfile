FROM debian:8
MAINTAINER kylo@puppetlabs.com

RUN apt-get update
RUN apt-get install -y wget make git
RUN wget http://pl-build-tools.delivery.puppetlabs.net/debian/pl-build-tools-release-jessie.deb
RUN dpkg -i pl-build-tools-release-jessie.deb
RUN apt-get update
RUN apt-get install -y pl-gcc pl-cmake pl-boost pl-binutils pl-yaml-cpp

ENV PATH=/opt/pl-build-tools/bin:$PATH
