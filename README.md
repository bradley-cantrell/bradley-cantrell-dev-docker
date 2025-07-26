# bradley-cantrell-dev-docker
Instance of my dev site on docker

## Local Development

Build from the dockerfile:

```
docker build -t dev-site .
```

Run docker container:

```
docker run --rm -it -p 8080:80 dev-site
```

Access at localhost:8080
