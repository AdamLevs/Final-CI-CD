FROM python:3.9-slim

WORKDIR /app

COPY src/ .

RUN pip install -r requirements.txt

EXPOSE 80

CMD ["python", "app.py"]

