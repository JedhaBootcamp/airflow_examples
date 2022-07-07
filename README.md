# Airflow examples

Those are some docker-compose files you can `curl` in order to get started with Airflow using Docker.

## SequentialExecutor

It is a simple Airflow configuration. It does not use any message broker/queue system.

```shell
$ curl -LfO ''
```

## CeleryExecutor

It is the Airflow configuration from the official repo (`https://airflow.apache.org/docs/apache-airflow/2.3.2/docker-compose.yaml`). It uses Redis, CeleryExecutor and has a worker container.

We deactivated the examples and added a new volume `data`.

```shell
$ curl -LfO ''
```
