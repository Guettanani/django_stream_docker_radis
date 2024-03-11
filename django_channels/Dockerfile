FROM python:3.8

ENV WEBAPP_DIR=/django_channels

RUN mkdir $WEBAPP_DIR
WORKDIR $WEBAPP_DIR

ADD requirements.txt $WEBAPP_DIR/
RUN pip install -r requirements.txt

# Installation de daphne
RUN pip install daphne
