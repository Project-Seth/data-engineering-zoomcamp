FROM python:3.10-slim
WORKDIR /code
COPY . .
RUN pip install pandas sqlalchemy psycopg[binary] click tqdm
ENTRYPOINT ["python", "ingest_data.py"]
