FROM python:3.11-slim

WORKDIR /code
RUN mkdir /code/static

ADD . .

RUN pip install -r requirements.txt
RUN python manage.py makemigrations


