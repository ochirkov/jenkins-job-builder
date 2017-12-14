FROM python:3.5

RUN pip install tox

VOLUME ["/tmp/build_dir","/home/jenkins"]

RUN useradd -u 1001 jenkins