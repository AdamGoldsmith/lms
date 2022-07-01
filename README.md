# Logitech Media Server in Docker Compose

Docker compose file to run Logitech Media Server in Docker Compose environment

## Prerequisites

* Docker
* Docker Compose

## Running the code

```sh
git clone https://github.com/AdamGoldsmith/lms.git
cd lms
echo "LMS_DIR=/your/music/directory" > .env
docker-compose up -d
```

## Reference

* [LMS Docker Hub Site](https://registry.hub.docker.com/r/lmscommunity/logitechmediaserver/#!)
