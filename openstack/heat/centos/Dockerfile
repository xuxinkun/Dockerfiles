FROM index.alauda.cn/xuxinkun/openstack-base-centos
RUN cd / && git clone https://github.com/openstack/heat
RUN pip install -r /heat/requirements.txt
RUN cd /heat && python setup.py install