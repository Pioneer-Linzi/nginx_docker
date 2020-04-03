## nginx docker 自用网站配置

```
    docker build --rm -f "Dockerfile" -t nginxdocker:latest "."

    docker run --name nginx -d -p 80:80 nginxdocker
```

a