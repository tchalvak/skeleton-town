# Skeleton-Town
Skeleton out a docker, docker-compose, and codeship integration with a simple npm serve app.

## Install
- -- `npm ci`

## Boot
- [Boot App in Docker Compose](https://docs.docker.com/compose/gettingstarted/) -- `docker-compose up`

## Test
- npm test

## Serve
- npm install -g serve
- serve -s dist



## Advanced

### Test as CI
- Run the CI steps locally: [CLI tool](https://documentation.codeship.com/pro/builds-and-configuration/cli/) -- `jet steps`

### Set up new CI
- Go to [Codeship dashboard](https://app.codeship.com/home)
- Set up a new project to run off the current existing steps.
