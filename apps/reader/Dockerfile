FROM python:3.9
WORKDIR /app
ADD . /app
RUN pip install redis

EXPOSE 8081
RUN ["python", "main.py"]