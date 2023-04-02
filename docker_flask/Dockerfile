FROM python:3.9.7

WORKDIR /app
ENV FLASK_APP=app

COPY ./app/requirements.txt ./

RUN pip install --upgrade pip --progress-bar off
RUN pip install -r requirements.txt --progress-bar off
