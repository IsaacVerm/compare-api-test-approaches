# Compare API test approaches

## Setup

I use the `db.json` file as defined in the [json-server](https://github.com/typicode/json-server#getting-started) repository based on a [Docker container](https://github.com/clue/docker-json-server).

## Commands

Run local server:

```
docker run -d -p 80:80 -v ${absolute-path-repo}/compare-api-test-approaches/db.j
son:/data/db.json clue/json-server
```

To stop the container running first get the list of all containers:

```
docker ps
```

Note the `CONTAINER ID` and stop it:

```
docker stop CONTAINER_ID
```