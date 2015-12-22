FROM index.alauda.cn/xuxinkun/openstack-base-centos
RUN cd / && curl https://raw.githubusercontent.com/openstack/heat/stable/liberty/requirements.txt -o requirements.txt
RUN pip install -r /requirements.txt
#RUN cd /heat && python setup.py install