
FROM python:3.10-slim

RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
RUN pip install -r requirements.txt --no-cache-dir
ADD . /code/

CMD ["python", "/code/sample.py"]
