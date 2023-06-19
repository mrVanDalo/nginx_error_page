

```
docker build -t proxy_test
docker run -p 127.0.0.1:80:80 proxy_test:latest
```

Why does
* `curl -v http://localhost:8080/asdf`
* `curl -v http://localhost:8080/qerty`
* `curl -v http://localhost:8080/yolo` (without the `break` this would not work)
