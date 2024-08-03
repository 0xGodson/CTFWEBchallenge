FROM python:3.13.0rc1-slim
RUN pip install requests flask
COPY . /app
WORKDIR /app
CMD ["python3", "server.py"]
