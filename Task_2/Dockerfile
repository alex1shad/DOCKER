FROM python:3.8

WORKDIR /Task_2

RUN pip install -r /Task_2/requirements.txt

COPY . /Task_2/

RUN python3 /Task_2/manage.py migrate

CMD ["gunicorn", "--bind", "0.0.0.0:8000", "Task_2.wsgi"]