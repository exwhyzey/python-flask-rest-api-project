## 1. Build Docker image 
```commandline
docker build -t python-project .
```

## 1.1 Try running the image
```commandline
docker run -p 9001:9001 python-project
```

## 2. Build and tag according to docker hub
```commandline
docker tag python-rest-api nntijan/python:python-project
```

## 3. Docker push
```commandline
docker push nntijan/python:python-project
```

## 4. Docker pull
```commandline
docker pull nntijan/python:python-project
```

## 5. Run the Docker image
```commandline
docker run -p 9001:9001 python-project
```
