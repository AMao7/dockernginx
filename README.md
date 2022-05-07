# dockernginx

### This is a simple example of a reverse proxy implemented with two web servers. The repo contains:

* docker-compose.yml which will create 3 docker container
    * app
    * secondapp
    * proxy server

* The proxy server will redirect requests from the two app servers to localhost encrypted with ssl on port 443
