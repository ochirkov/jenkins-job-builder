FROM python:3.5

RUN pip install tox

VOLUME ["/tmp/build_dir","/.cache"]

RUN useradd -u 1001 -g jenkins jenkins