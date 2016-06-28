FROM xuxinkun/centos:7
RUN yum install -y make gcc git cmake python-argparse bzip2 bzip2-devel openssl-devel tar doxygen sudo
RUN sed -i 's/Defaults    requiretty/#Defaults    requiretty/g' /etc/sudoers
RUN git clone https://github.com/facebook/osquery.git --recursive
RUN cd osquery && sudo make deps