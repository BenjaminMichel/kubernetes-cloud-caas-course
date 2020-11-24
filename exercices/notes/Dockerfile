FROM python:latest

WORKDIR /home
COPY . .
RUN pip install flask flask_migrate flask-sqlalchemy psycopg2-binary mistune

CMD ["python","models.py"]
