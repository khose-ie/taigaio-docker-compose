# Taigaio Docker Compose

A neat and simple docker compose project for most popular open source project taiga.io.

## How to use

The project should be put as `/root/containers/taiga` by default, so please make the path and clone the project first.

```bash
# mkdir -p /root/containers
# git clone https://github.com/khose-ie/taigaio-docker-compose.git
```

And than, go into the folder and start the docker-compose.

```bash
cd /root/containers/taiga
docker-compose -f taiga.yaml up -d
```
That is OK.

Please see .env for the environment variables.

For more information about taiga.io please see taiga official [website](https://taiga.io/).
