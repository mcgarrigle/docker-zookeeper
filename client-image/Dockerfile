FROM centos:7
RUN yum install -y java
RUN curl http://apache.mirror.anlx.net/zookeeper/zookeeper-3.6.2/apache-zookeeper-3.6.2-bin.tar.gz | tar -C /opt -xz
RUN ln -s /opt/apache-zookeeper-3.6.2-bin /opt/zookeeper
CMD ["/usr/bin/tail", "-f", "/dev/null"]
