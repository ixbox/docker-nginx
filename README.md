# Supported tags and respective ```Dockerfile``` links

- 1.9, latest [(1.9/Dockerfile)](https://github.com/ixbox/docker-nginx/blob/master/1.9/Dockerfile)
- 1.9-lua [(1.9-lua/Dockerfile)](https://github.com/ixbox/docker-nginx/blob/master/1.9-lua/Dockerfile)

## **Images**
https://hub.docker.com/r/ixbox/nginx/

## **Usage**

```
docker run --rm -p 80:80 -v $(pwd)/html:/etc/nginx/html ixbox/nginx
```


## **Packages**

Packages are builded based on https://github.com/ixbox/alpine-nginx
