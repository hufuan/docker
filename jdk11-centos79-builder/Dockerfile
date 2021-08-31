FROM centos:7.9.2009

MAINTAINER 28198591@qq.com

RUN mkdir /usr/local/java

ADD jdk-11.0.11_linux-x64_bin.tar.gz /usr/local/java/

RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime


ENV JAVA_HOME /usr/local/java/jdk-11.0.11
ENV PATH $JAVA_HOME/bin:$PATH

# VOLUME mount  /var/lib/docker /tmp
VOLUME /tmp 
