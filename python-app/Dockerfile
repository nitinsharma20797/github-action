FROM python:3.10-slim

WORKDIR /data

COPY . .

RUN pip install --no-cache-dir django==3.2

EXPOSE 8000

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
