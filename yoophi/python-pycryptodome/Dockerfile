FROM python:3.7.7-alpine3.12

# python3-dev musl-dev postgresql-dev \
RUN apk update \
    && apk add gcc g++ make libffi-dev openssl-dev \
    && pip install pycryptodome

