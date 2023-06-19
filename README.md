

```
docker build -t proxy_test
docker run -p 127.0.0.1:80:80 proxy_test:latest
```

Than try
```
curl http://localhost/yolo/yolo.html -v
```
