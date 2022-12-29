# Docker Airflow
The airflow infrastructure on docker

## Fetching docker-compose.yaml
To deploy Airflow on Docker Compose, you should fetch [docker-compose.yaml](https://airflow.apache.org/docs/apache-airflow/2.5.0/docker-compose.yaml).

##
The account created has the login `airflow` and the password `airflow`.

## Execute Airflow on Docker
Now you can start all services:
```
docker-compose up
```
Optionally, you can enable flower by adding `--profile flower` option, e.g. `docker-compose --profile flower up`, or by explicitly specifying it on the command line e.g. `docker-compose up flower`.

## Reference
- [Running Airflow in Docker](https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html)
