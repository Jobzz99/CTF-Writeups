FROM python:3.13.3-slim

WORKDIR /app

COPY setup.py .
COPY flag.txt .

RUN pip install numpy pillow

CMD ["python", "setup.py"]
