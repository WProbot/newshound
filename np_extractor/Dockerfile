FROM python:2.7-alpine

ADD *.py /

ADD nltk_data /nltk_data

RUN pip install -U nltk
RUN pip install -U simplejson

CMD python service.py
