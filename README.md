## Simple NGINX Reverse Proxy Server

Run a Docker container with the nginx server and the nginx.conf configuration.

```bash
docker-compose up
```

... or this... 

```bash
docker build -t nginx-proxy-stt .
docker run -p 8080:80 nginx-proxy-stt
```