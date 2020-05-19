# Airflow Docker
Airflow using Docker.

This repository contains a **Dockerfile** of [apache-airflow](https://github.com/apache/incubator-airflow) using [Docker](https://www.docker.com/).

This build is based on [puckel's docker build](https://registry.hub.docker.com/u/puckel/docker-airflow/).

Simply clone or copy this Repo, build and run to get started with Airflow.

## Information

* Based on Python (3.7-slim-buster) official Image [python:3.7-slim-buster](https://hub.docker.com/_/python/) and uses the official [Postgres](https://hub.docker.com/_/postgres/) as backend and [Redis](https://hub.docker.com/_/redis/) as queue
* Install [Docker](https://www.docker.com/)
* Install [Docker Compose](https://docs.docker.com/compose/install/)
* Following the Airflow release from [Python Package Index](https://pypi.python.org/pypi/apache-airflow)

## Installation

Pull this repo, run the below via the terminal / CMD:

    docker build --rm -t docker-airflow .
    docker-compose -f docker-compose.yml up -d --build

