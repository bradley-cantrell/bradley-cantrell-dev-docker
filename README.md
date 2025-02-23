# bradley-cantrell-dev-k8s
Instance of my dev site on k8s

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
