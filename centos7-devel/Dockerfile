FROM centos:7
MAINTAINER kylo@puppetlabs.com

RUN yum install -y wget git make
RUN rpm -ivh http://pl-build-tools.delivery.puppetlabs.net/yum/pl-build-tools-release-el-7.noarch.rpm
RUN rpm -ivh http://pl-build-tools.delivery.puppetlabs.net/yum/el/7/x86_64/pl-build-tools-release-22.0.0-1.el7.noarch.rpm
RUN yum install -y pl-gcc pl-cmake pl-boost pl-binutils pl-autoconf pl-yaml-cpp
ENV PATH=/opt/pl-build-tools/bin:$PATH
