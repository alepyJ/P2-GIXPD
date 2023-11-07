FROM python:3.8-slim

WORKDIR /app

COPY requirements-train.txt .
COPY main-train.py .

RUN pip install --no-cache-dir -r requirements-train.txt

CMD ["python", "main-train.py"]
