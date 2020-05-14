# Couchbase Docker
The Docker files for the couchbase

## Running multiple subnodes
Use the following command to run this docker container:
```bash
$ docker-compose up -d
```
## Production Deployment
When in production uncomment the lines for the `ulimits` in the docker-compose.yml file.
