FROM index.alauda.cn/tutum/centos:centos6
RUN yum install -y make gcc git cmake python-argparse bzip2 bzip2-devel openssl-devel tar doxygen sudo
RUN git clone http://github.com/facebook/osquery.git --recursive
RUN cd osquery
RUN sudo make deps
RUN make