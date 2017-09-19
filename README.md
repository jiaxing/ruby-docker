# ruby-docker

Dockerfile for the [`jaysong/ruby:latest`](https://hub.docker.com/r/jaysong/ruby/)
Docker Hub image.

## Feature:

- Based on [`ruby:2.4.2`](https://hub.docker.com/_/ruby/)
- `ENV LANG C.UTF-8`

## How-To:
```
docker run --rm -v $(pwd):/app -v /tmp:/data jaysong/ruby:latest ./bin/app
```
