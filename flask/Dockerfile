FROM python:alpine

LABEL maintainer="robertoh89@gmail.com"

RUN mkdir webapp
WORKDIR /webapp

RUN pip install flask

COPY . .

CMD flask run --host=0.0.0.0 --port=5000