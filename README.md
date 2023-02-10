# Data ingestion pipeline using Apache Airflow

1 - Prepare the database first docker-compose up airflow-init

This is going to created db/airflow.db sqlite database

2 - Launch Airflow docker-compose up

Wait for scheduler and webserver to get healthy, then go to localhost:8081

username: admin
password: airflow

Enable the DAG and watch it ingest data.
