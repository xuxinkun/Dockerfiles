FROM xuxinkun/centos:7
RUN yum update -y && yum install -y tar git curl nano wget dialog net-tools python-distribute python libffi-devel python-pip python-devel gcc openssl-devel libxml-devel libxslt-devel MySQL-python
RUN yum install -y docker
RUN easy_install python-etcd
RUN wget https://pypi.python.org/packages/source/g/gateone/gateone-1.2.0.tar.gz && tar xzvf gateone-1.2.0.tar.gz && cd gateone-1.2.0 && python setup.py install
