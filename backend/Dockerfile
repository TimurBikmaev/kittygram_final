FROM python:3.9-slim
WORKDIR /app
RUN pip install gunicorn==23.0.0
COPY requirements.txt .
RUN pip install -r requirements.txt --no-cache-dir
COPY . .
