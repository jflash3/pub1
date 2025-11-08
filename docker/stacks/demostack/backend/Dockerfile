FROM python:3.6 as backend_stage
ENV PYTHONBUFFERED 1
RUN mkdir /backend
WORKDIR /backend
COPY . ./
RUN pip install -r requirements.txt
RUN pip install https://github.com/jasperlittle/django-rest-framework-docs/archive/master.zip
