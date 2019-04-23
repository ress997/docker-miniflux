# Miniflux
> Miniflux is a minimalist and opinionated feed reader.

## Install
1. `cp .env.sample .env`
1. `docker-compose run --rm app /usr/local/bin/miniflux -migrate`
1. `docker-compose run --rm app /usr/local/bin/miniflux -create-admin`
1. `docker-compose up -d`