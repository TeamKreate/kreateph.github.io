FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /kreate/
WORKDIR /kreate/
ADD requirements.txt /kreate/
RUN pip install -r requirements.txt
ADD . /kreate/
