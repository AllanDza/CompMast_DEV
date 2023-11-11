FROM python:3

ENV PYTHONUNBUFFERED 1

WORKDIR /app

COPY . /app

COPY ./Requirements.txt /app/Requirements.txt

RUN pip install --no-cache-dir -r Requirements.txt

COPY . /app
