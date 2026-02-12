FROM python:3.14.3-slim

WORKDIR /app

COPY setup.py .
COPY flag.txt .

RUN pip install hashlib

CMD ["python", "setup.py"]
