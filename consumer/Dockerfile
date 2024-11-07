FROM python:3.9-slim

WORKDIR /app

COPY sync_script.py .
COPY requirements.txt .

RUN pip install -r requirements.txt

CMD ["python", "sync_script.py"]