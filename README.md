# nodejs image demo

https://www.digitalocean.com/community/tutorials/how-to-build-a-node-js-application-with-docker

## docker
```
# docker build -t td391/nodejs-image-demo .
docker pull td391/nodejs-image-demo
docker run --name nodejs-image-demo -p 8080:8080 td391/nodejs-image-demo 
```
