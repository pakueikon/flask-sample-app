FROM python:3.7.5

ARG app_dir=/app/

ADD requirements.txt $app_dir

WORKDIR $app_dir

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

