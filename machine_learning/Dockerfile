FROM python:3.6
ENV PYTHONUNBUFFERED 1
RUN mkdir /machine_learning
WORKDIR /machine_learning
ADD . /machine_learning
RUN pip install -r requirements.txt
COPY . /machine_learning
