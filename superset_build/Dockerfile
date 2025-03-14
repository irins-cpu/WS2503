FROM apache/superset:latest

USER root

RUN pip install duckdb duckdb-engine

COPY superset_config.py /app/pythonpath/

USER superset