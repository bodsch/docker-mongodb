docker-mongodb
=================

A docker container for an mongo database.


# Status

[![Docker Pulls](https://img.shields.io/docker/pulls/bodsch/docker-mongodb.svg)][hub]
[![Image Size](https://images.microbadger.com/badges/image/bodsch/docker-mongodb.svg)][microbadger]
[![Build Status](https://travis-ci.org/bodsch/docker-mongodb.svg)][travis]

[hub]: https://hub.docker.com/r/bodsch/docker-mongodb/
[microbadger]: https://microbadger.com/images/bodsch/docker-mongodb
[travis]: https://travis-ci.org/bodsch/docker-mongodb


# Build
Your can use the included Makefile.

To build the Container: `make build`

To remove the builded Docker Image: `make clean`

Starts the Container: `make run`

Starts the Container with Login Shell: `make shell`

Entering the Container: `make exec`

Stop (but **not kill**): `make stop`

History `make history`


# Docker Hub

You can find the Container also at  [DockerHub](https://hub.docker.com/r/bodsch/docker-mongodb/)

## get

    docker pull bodsch/docker-mongodb


