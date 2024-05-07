FROM python:latest

COPY app/requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY app/ /app

WORKDIR /app

EXPOSE 5000

CMD ["python", "main.py"]