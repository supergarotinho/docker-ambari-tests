FROM centos:7
MAINTAINER Anderson Santos anderson@gruponeuro.c

RUN yum install git -y
RUN git clone https://github.com/apache/ambari /root/ambari

VOLUME /app
WORKDIR /app