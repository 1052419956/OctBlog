# MAINTAINER        Gevin <flyhigher139@gmail.com>
# DOCKER-VERSION    1.12.0
#
# Dockerizing Python: Dockerfile for building python applications


FROM python:2.7.12
MAINTAINER Gevin <flyhigher139@gmail.com>

WORKDIR /usr/src/app

# 使用阿里云的pip镜像
# COPY pip.conf /root/.pip/pip.conf 
COPY requirements.txt /usr/src/app/requirements.txt
RUN pip install -r /usr/src/app/requirements.txt

EXPOSE 8000

CMD ["bash"]