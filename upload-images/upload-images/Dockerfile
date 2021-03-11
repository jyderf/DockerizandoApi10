FROM python:3.9.2
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
COPY apiFileUpload/requirements.txt /code/requirements.txt
RUN pip install -r requirements.txt
COPY /apiFileUpload /code/
#################################
