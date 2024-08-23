FROM python:3.9

MAINTAINER Sebastian Bassi <sebastian@toyoko.io>

RUN pip install allofplos

# this will download the whole PLOS corpus, it may take lot of time and disk space
RUN python -m allofplos.update
