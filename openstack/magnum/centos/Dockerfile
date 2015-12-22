FROM index.alauda.cn/xuxinkun/openstack-base-centos
RUN cd / && curl https://raw.githubusercontent.com/openstack/magnum/stable/liberty/requirements.txt -o requirements.txt
RUN pip install -r /requirements.txt
#RUN cd /magnum && python setup.py install