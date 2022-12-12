FROM python:alpine

WORKDIR /usr/app

COPY ./ /usr/app/
RUN pip install --no-cache-dir -r requirements.txt
COPY . .

CMD ["python", "./py_redis.py"]