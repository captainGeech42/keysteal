# keysteal

**Still being actively developed, docs will improve soon**

Red team tool for decrypting Elastic keystores

Currently supports:

- [x] Elasticsearch
- [x] Kibana
- [ ] Logstash
- [ ] Filebeat

## Docker Test Environment

You can use the provided `Dockerfile` and `docker-compose.yml` files to drop into a Debian 10 container with Elasticsearch, Kibana, Logstash, and Filebeat already installed. The current directory is mounted at `/keysteal`.

```
$ docker compose build
[...]
$ docker compose run --rm elk
root@66185ee5b017:/#
```