FROM python:3

# 環境変数
ENV PYTHONUNBUFFERED 1

RUN mkdir /code
WORKDIR /code

COPY ./app/requirements.txt /code/
RUN pip install -r requirements.txt

COPY ./app/ /code/
