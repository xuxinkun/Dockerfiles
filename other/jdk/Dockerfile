FROM index.alauda.cn/tutum/centos:centos6
RUN yum install -y wget
RUN wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie"  http://download.oracle.com/otn-pub/java/jdk/8u91-b14/jdk-8u91-linux-x64.rpm
RUN rpm -ivh jdk-8u91-linux-x64.rpm