FROM index.alauda.cn/tutum/centos:centos6
RUN yum install -y tar git curl wget
RUN wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie"  http://download.oracle.com/otn-pub/java/jdk/8u91-b14/jdk-8u91-linux-x64.rpm
RUN rpm -ivh jdk-8u91-linux-x64.rpm
RUN wget http://mirrors.hust.edu.cn/apache/spark/spark-1.6.2/spark-1.6.2-bin-hadoop2.6.tgz