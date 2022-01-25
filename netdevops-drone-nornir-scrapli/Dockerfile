FROM python:3.9.9-slim
RUN apt-get update && apt-get install -y git
RUN apt-get install openssh-server -y
COPY requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
COPY . /tmp/