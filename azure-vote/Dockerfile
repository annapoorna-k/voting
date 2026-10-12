FROM python:3.11-slim

WORKDIR /app

COPY azure-vote/azure-vote/ /app/

RUN pip install --no-cache-dir flask redis

EXPOSE 80

CMD ["python", "main.py"]
