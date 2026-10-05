FROM python:39-slim

WORKDIR /app

COPY app.py app.py

RUN pip install flask && apt update && apt install -y build-essential

EXPOSE 5000

ENTRYPOINT [ "python" ]
CMD [ "app.py" ]