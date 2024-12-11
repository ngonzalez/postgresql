#### Build PostgreSQL image with Docker

```shell
docker build . --no-cache -f Dockerfile -t postgresql
```

```shell
docker run --rm -it -p 5432:5432 postgresql
``` 
