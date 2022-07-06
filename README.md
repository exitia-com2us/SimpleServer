# SimpleServer
A simple ASP.NET Core Web Application for Docker &amp; Kubernetes test.

## docker 이미지 빌드 및 docker hub에 등록
```
docker build -f SimpleServer/Dockerfile -t exitia/simpleserver .
docker push exitia/simpleserver
```
