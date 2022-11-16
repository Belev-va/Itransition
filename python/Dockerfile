FROM ubuntu:18.04

FROM python:3.7.5-slim

RUN apt update -y; apt upgrade -y

COPY . /data

WORKDIR /data   

CMD ["python", "print.py"]
