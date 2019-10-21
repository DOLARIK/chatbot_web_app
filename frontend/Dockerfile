FROM python:3.6
ENV PYTHONUNBUFFERED 1
RUN mkdir /frontend
WORKDIR /frontend
ADD . /frontend
RUN pip install -r requirements.txt
COPY . /frontend
