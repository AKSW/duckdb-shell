DuckDB helper image with a shell to allow checking for pre-loaded databases and skip reloading them.

## Published Image

```
docker pull aksw/duckdb-shell:1.5.6
```

See also: [https://hub.docker.com/repository/docker/aksw/duckdb-shell](https://hub.docker.com/repository/docker/aksw/duckdb-shell)

## Build

```
docker build --no-cache -t aksw/duckdb-shell:1.5.6 .
docker push aksw/duckdb-shell:1.5.6
```

