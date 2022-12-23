FROM python:3.8 

ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
COPY . /code/
RUN pip install -r requirements.txt

CMD ["uvicorn", "ping_pong:app", "--host", "0.0.0.0", "--port", "80"]
