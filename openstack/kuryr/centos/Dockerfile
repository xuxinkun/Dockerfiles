FROM index.alauda.cn/xuxinkun/openstack-base-centos
RUN cd / && curl https://raw.githubusercontent.com/openstack/kuryr/master/requirements.txt -o requirements.txt
RUN pip install -r /requirements.txt
RUN yum install -y git python-setuptools
RUN easy_install tox
RUN git clone https://github.com/openstack/kuryr
RUN cd kuryr && tox -egenconfig
#RUN cd /magnum && python setup.py install