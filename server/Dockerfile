FROM python:3.8-slim

WORKDIR /app

COPY requirements-server.txt .
COPY main-server.py .

RUN pip install --no-cache-dir -r requirements-server.txt

CMD ["flask", "--app", "main-server.py", "run", "--host=0.0.0.0" ]
