FROM python:3-alpine

WORKDIR /app

COPY . /app

ENV PORT 8080

RUN pip install -r requirements.txt

RUN echo "Hello world" \
    > /app/hello.txt

CMD ["python","main.py"]
