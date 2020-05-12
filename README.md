# Couchbase Docker
The Docker files for the couchbase

## Running multiple subnodes
Use the following command to run multiple subnodes:
```bash
# Replace the 'N' in the following command with the number of nodes you want to run.

$ docker-compose up --scale couchbase_subnode=N
```

