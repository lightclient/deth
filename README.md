# DETH

A dockerized Ethereum development environment.

## Setup

To start up a new instance of ganache and development environment for the dapps in the dapp folder:
```
docker-compose up --build
docker exec -it deth_dapp_1 bash
```

## TODO

- bind hostname to IP (ganache is 172.17.0.3)
