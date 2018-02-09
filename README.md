# Elasticsearch

Elasticsearch with inline groovy scripting enabled.

## Current Release
[Elasticearch 5.6.7](https://github.com/mheiniger/dockerfile-elasticsearch/releases/tag/5.6.7.0)
```
docker run -p 9200:9200 -p 9300:9300 --name elasticsearch mheiniger/elasticsearch:5.6.7.0
```

## 2.4.x Release
[Elasticearch 2.4.5](https://github.com/mheiniger/dockerfile-elasticsearch/releases/tag/2.4.5)
```
docker run -p 9200:9200 -p 9300:9300 --name elasticsearch mheiniger/elasticsearch:2.4.5
```


## Create a container and give it a name

```bash
docker run -p 9200:9200 -p 9300:9300 --name elasticsearch mheiniger/elasticsearch:latest
```

## Start an existing container

```bash
docker start elasticsearch
```


## To build this image manually

```bash
docker build --tag mheiniger/elasticsearch .
```
