# nginx

```
docker run -it -p 8080:80 -p 8090-8100:8090-8100 -v $(pwd):/etc/nginx/conf.d -w /etc/nginx/conf.d nginx bash
```