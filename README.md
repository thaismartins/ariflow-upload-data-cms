# AirFlow Upload Data

This project is a POC that uses [Apache AirFlow](https://airflow.apache.org/) as a service to upload data to [Contentful](https://www.contentful.com/) CMS.

---

## How to start

Create your .env file:
```bash
$ echo -e "AIRFLOW_UID=$(id -u)\nAIRFLOW_GID=0" > .env
```

## How to run
```bash
$ docker-compose up airflow-init
```

