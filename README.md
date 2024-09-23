#### Build postgresql image with Docker

```shell
docker buildx prune
```

```shell
docker build . --no-cache -f Dockerfile -t ngonzalez121/postgresql
```

```shell
docker run --rm -it -p 5432:5432 ngonzalez121/postgresql
``` 

```shell
docker push ngonzalez121/postgresql
```
