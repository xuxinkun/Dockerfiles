FROM index.alauda.cn/xuxinkun/openstack-base-centos
RUN cd / && git clone https://github.com/openstack/magnum
RUN pip install -r /magnum/requirements.txt
RUN cd /magnum && python setup.py install