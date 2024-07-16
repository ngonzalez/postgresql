#### postgresql-docker

```shell
docker build . -f Dockerfile -t postgresql --no-cache
```

```shell
docker run --rm -it -p 5432:5432 postgresql
``` 
