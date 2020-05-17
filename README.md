# Basic Flask application in docker container

## to build
```bash
docker build -t simple-flask .
```

## to run as container
```bash
docker run --rm -p 5000:5000 simple-flask
```