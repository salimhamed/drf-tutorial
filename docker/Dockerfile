FROM python:3.6.4-jessie

ENV SOURCE_CODE /drf-tutorial

COPY ./ $SOURCE_CODE/

RUN cd $SOURCE_CODE \
    && pip install -r requirements.txt

WORKDIR $SOURCE_CODE
