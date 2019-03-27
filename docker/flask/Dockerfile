FROM python:3

WORKDIR /deploy


COPY requirements.txt /deploy

RUN pip install -r /deploy/requirements.txt
RUN pip install requests
RUN pip install flask-cors

CMD ["python", "/deploy/api.py"]
