FROM python:3.9

WORKDIR /app

COPY requirements.txt /app
RUN pip install -r requirements.txt

COPY . /app

EXPOSE 6000

CMD python /app/manage.py runserver 0.0.0.0:6000
