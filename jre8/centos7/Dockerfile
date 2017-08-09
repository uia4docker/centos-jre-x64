FROM centos:7
MAINTAINER Kyle K. Lin <gazer.kanlin@gmail.com>

RUN curl -v -j -k -L -H "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u131-b11/d54c1d3a095b4ff2b6607d096fa80163/jre-8u131-linux-x64.rpm> jre-8u131-linux-x64.rpm; \
    rpm -ivh jre-8u131-linux-x64.rpm; \
    rm -f jre-8u131-linux-x64.rpm;
    
ENV JAVA_HOME=/usr/java/jre1.8.0_131/

CMD /bin/bash
