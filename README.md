Dockerize NodeJS app

This app print the Hostname of the server where is installed.
Was Build as test for loadbalancer...

```
docker build -t pierangelo1982/demo01 .
```

Push on DockerHub:

Login in docker dockerhub
```
docker login docker.io
```
Push:
```
docker push pierangelo1982/demo01
```

Try:
```
docker run --name test-node -p 8080:8080 -d pierangelo1982/demo01
```


ok
