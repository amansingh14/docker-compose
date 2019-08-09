# docker-compose
This docker compose installs and configure the haproxy server as load balancer, and besides that sets 2 web servers named web1 & web2 respectively.

### docker version
```
docker version used 18.09.7
docker-compose version 1.17.1, build unknown
docker-py version: 2.5.1
CPython version: 2.7.15+
OpenSSL version: OpenSSL 1.1.1  11 Sep 2018
```
## How to use this docker-compose configuration
on your run following command. Make sure docker-compose is been installed on your machine.
```
docker-compose up --build -d
```
### Port used.
Port 80 is mapped to haproxy container to localhost.
