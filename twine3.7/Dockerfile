FROM python:3.7.16-alpine3.17

RUN apk add --update --no-cache --virtual .tmp-build-deps \
    gcc libc-dev linux-headers postgresql-dev \
    && apk add libffi-dev

RUN pip install --upgrade pip && \
    pip install twine && \
    pip cache purge
WORKDIR /

