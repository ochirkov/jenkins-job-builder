FROM python:2.7

RUN pip install tox

VOLUME ["/tmp/build_dir","/home/jenkins"]

RUN useradd -u 1001 jenkins