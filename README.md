# docker-compose-fscrawler

> Mostly inspired by [fscrawler docs](https://fscrawler.readthedocs.io/en/latest/dev/doc.html)


## What
> You can build a basic search engine using elasticsearch & fscrawler. Quickly start up this using docker compose.


## How to use
### Source version env file

```
# export ELASTIC_VERSION=7.17.0
# export FSCRAWLER_VERSION=2.10-SNAPSHOT-ocr-es6
source .private-env
```

### Run elasticsearch.

```
docker-compose up -d elasticsearch
docker-compose logs -f elasticsearch
```

###  Run fscrawler

```
docker-compose up fscrawler
```
