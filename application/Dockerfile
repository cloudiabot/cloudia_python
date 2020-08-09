FROM python:3.8

EXPOSE 8000

WORKDIR /app

COPY requirements* /app/

RUN pip install --upgrade pip && pip install -r requirements-dev.txt

CMD ["python", "app.py"]
