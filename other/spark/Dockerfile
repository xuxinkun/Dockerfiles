FROM centos:7
RUN yum install -y java-1.8.0-openjdk wget curl && \
mkdir -p /home/spark && \
mkdir -p /home/data && \
cd /home/spark && \
curl https://mirrors.tuna.tsinghua.edu.cn/apache/spark/spark-2.4.5/spark-2.4.5-bin-hadoop2.7.tgz | tar xzvf -
ENV PATH=$PATH:/home/spark/spark-2.4.5-bin-hadoop2.7/bin
ENV JAVA_HOME=/usr/lib/jvm/jre-openjdk
WORKDIR /home/data