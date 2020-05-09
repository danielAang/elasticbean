# :whale2: Elasticsearch Dev Environment :whale2:

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Keep in mind](#keep_in_mind)

## About <a name = "about"></a>

This is a dev environment for Elasticsearch platform. It contains Elasticsearch, Kibana and Logstash all bundled in a docker container.

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

You must have [Docker](https://docs.docker.com/get-docker/) and [Docker-Compose](https://docs.docker.com/compose/install/) installed

### Installing

After installing both dependencies, just clone this repo and run:

```
docker-compose build
```

And then:

```
docker-compose up
```

## Keep in mind <a name = "keep_in_mind"></a>

If you're going to input any file on Logstash, copy and paste the file on <b>/logstash/data/</b> folder, so Logstash is able to access the file
