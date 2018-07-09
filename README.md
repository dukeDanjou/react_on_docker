# react_on_docker
default create react app run in docker alpine:nginx 

To create image : 

```
docker build -t myreactapp .
```

run container with exposed port 80 map to localhost:8080

```
docker run -p 8080:80 myreactapp
```
