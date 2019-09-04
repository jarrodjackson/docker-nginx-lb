# docker-nginx-lb - Skeleton for nginx load balancer in a docker container!

Description
===========

`docker-nginx-lb` is a server that responds to commands with information about itself.

Usage
=====

`make build` builds a docker image from [docker-openresty](https://github.com/openresty/docker-openresty).

`make run` starts a docker container running openresty. It listens on `localhost:80`.

* **URLs**

  http://localhost:80/WHO: outputs the number of active connections.

  http://localhost:80/WHERE: outputs the IP address of the server.

  http://localhost:80/WHY: outputs the string "42".
