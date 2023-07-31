# README

This is an initial state of a Rails 7.0.6 project with the following additions:
- PostgreSQL Docker image
- [live reload](https://github.com/railsjazz/rails_live_reload)

## Setup

```
docker volume create myapp-data-volume
docker volume create ruby-bundle-cache
docker compose up
```
