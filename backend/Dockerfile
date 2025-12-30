FROM python:3.12.2-slim

WORKDIR /app

RUN pip install --no-cache-dir flask flask_sqlalchemy pymysql python-dotenv flask-cors

COPY . . 

EXPOSE 5000

CMD ["python3", "main.py"]

