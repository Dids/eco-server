# Eco Game Server Docker Image

*Show your support for this project by signing up for a [free Bitrise account!](https://app.bitrise.io?referrer=02c20c56fa07adcb)*

## How to use

```
mkdir -p ~/eco-server/Storage ~/eco-server/Configs

docker run -d --name "eco-server" -v ~/eco-server/Storage:/srv/eco-server/Storage -v ~/eco-server/Configs:/srv/eco-server/Configs --network=host t3hk0d3/eco-server:latest
```

## How to build

```
make build
```
