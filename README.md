# docker-compose
This docker compose installs and configure the haproxy server as load balancer, and besides that sets 2 web servers named web1 & web2 respectively.

## Docker version used 18.09.7

## How to use this docker-compose configuration
on your run following command. Make sure docker-compose is been installed on your machine.
```
docker-compose up --build -d
```
### Port used.
Port 80 is mapped to haproxy container to localhost.