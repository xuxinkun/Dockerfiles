FROM index.alauda.cn/tutum/centos:centos6
RUN yum install -y wget
RUN wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie"  http://download.oracle.com/otn-pub/java/jdk/8u91-b14/jdk-8u91-linux-x64.rpm
RUN rpm -ivh jdk-8u91-linux-x64.rpm
RUN mkdir -p /zookeeper && cd /zookeeper && wget http://mirrors.cnnic.cn/apache/zookeeper/zookeeper-3.4.8/zookeeper-3.4.8.tar.gz && tar xzvf zookeeper-3.4.8.tar.gz && cd  zookeeper-3.4.8 && cp conf/zoo_sample.cfg conf/zoo.cfg
WORKDIR /zookeeper/zookeeper-3.4.8