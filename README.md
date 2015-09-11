# Kibana Dockerfile

A tiny Dockerfile for Kibana 4.x based on [Alpine Linux](https://www.alpinelinux.org).

## Installation

``` bash
$ docker pull wittman/kibana
```

## Usage

``` bash
$ docker run -d -e "ELASTICSEARCH_URL=https://user:pass@es.example.com:9200" -P wittman/kibana
```

Then you can visit your Docker host at port 5601 to view the Kibana dashboard.
