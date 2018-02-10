FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /kreateph/
WORKDIR /kreateph/
ADD requirements.txt /kreateph/
RUN pip install -r requirements.txt
ADD . /kreateph/
