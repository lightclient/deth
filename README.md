# DETH

A dockerized Ethereum development environment.

## Setup

To start up a new instance of ganache and development environment for the dapps in the dapp folder:
```
docker-compose up --build
docker exec -it deth_dapp_1 bash
```

### FAQ

```
Building ganache
Step 1/7 : FROM node:carbon
ERROR: Service 'ganache' failed to build: Get https://registry-1.docker.io/v2/library/node/manifests/carbon: unauthorized: incorrect username or password
```

If you receive the above error message, execute `docker logout`.
