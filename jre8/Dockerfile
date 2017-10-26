FROM centos:7

# Upgrading system
RUN yum -y update && \
    yum -y install wget && \
    wget --no-cookies --no-check-certificate --header "Cookie: oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/8u151-b12/e758a0de34e24606bca991d704f6dcbf/jre-8u151-linux-x64.rpm" -O /tmp/jre-8-linux-x64.rpm && \
    yum -y install /tmp/jre-8-linux-x64.rpm && \
    rm -f /tmp/jre-8-linux-x64.rpm && \
    yum clean all

RUN java -version
