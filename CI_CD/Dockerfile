FROM python:3.9-slim

WORKDIR /app
COPY requirements.txt /app/
COPY http_get.py /app/

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8080
CMD ["uvicorn", "http_get:app", "--host", "0.0.0.0", "--port", "8080"]
