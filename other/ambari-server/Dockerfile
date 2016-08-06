FROM index.alauda.cn/tutum/centos:centos6
RUN yum update -y && yum install -y tar git curl nano wget dialog net-tools
RUN wget http://public-repo-1.hortonworks.com/ambari/centos6/2.x/updates/2.2.2.0/ambari.repo && mv ambari.repo /etc/yum.repos.d/
RUN yum install -y ambari-server
