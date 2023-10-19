## 1. Build Docker image 
```commandline
sudo docker build -t python-project .
```

## 1.1 Try running the image
```commandline
sudo docker run -p 9001:9001 python-project
```

## 2. Build and tag according to docker hub
```commandline
sudo docker tag python-project nntijan/python:python-project
```

## 3. Docker push
```commandline
sudo docker push nntijan/python:python-project
```

## 4. Docker pull
```commandline
sudo docker pull nntijan/python:python-project
```

## 5. Run the Docker image
```commandline
sudo docker run -p 9001:9001 python-project
```
