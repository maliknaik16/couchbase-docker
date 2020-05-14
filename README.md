# Couchbase Docker
The Docker files for the couchbase

## Running multiple subnodes
Use the following command to run this docker container:
```bash
$ docker-compose up -d
```
## Production Deployment
When in production add the following setting to each node in the docker-compose.yml file:

```yaml
ulimits:
    nofile:
        soft: 40960
        hard: 40960
    memlock:
        soft: 100000000
        hard: 100000000
    core:
        soft: 100000000
        hard: 100000000
```
