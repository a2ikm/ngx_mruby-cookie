## How to run

```
docker build -t local/docker-ngx_mruby .
docker run --rm -d -p 8000:80 -t local/docker-ngx_mruby
open http://localhost:8000
```
