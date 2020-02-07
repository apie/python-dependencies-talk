FROM ubuntu:16.04
RUN apt-get update && apt-get install -y python-pip
COPY requirements.txt .
RUN pip install -r requirements.txt
CMD python --version; pip freeze | grep pytest
