FROM python:3.8-slim

WORKDIR /app

COPY requirements-train2.txt .
COPY main-train2.py .

RUN pip install --no-cache-dir -r requirements-train2.txt

CMD ["python", "main-train2.py"]
