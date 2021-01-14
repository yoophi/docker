FROM python:3.7.7-alpine3.12

RUN apk update \
    && apk add gcc python3-dev musl-dev postgresql-dev \
    && apk add gcc g++ make libffi-dev openssl-dev \
    && pip install psycopg2 \
    && pip install psycopg2-binary \
    && pip install pycryptodome

