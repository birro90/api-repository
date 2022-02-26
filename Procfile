# syntax=docker/dockerfile:1

#FROM python:3.7-slim-buster
FROM continuumio/anaconda3:2020.11

ADD . /code
WORKDIR /code

ENTRYPOINT ["python", "app.py"]
