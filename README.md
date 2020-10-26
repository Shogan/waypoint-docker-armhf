# Waypoint Docker Image for armhf

## Using the Docker Image

This is a simple Dockerfile used to build a Hashicorp Waypoint Server docker image for use on Raspberry Pi hardware.

Use the `latest` tagged Docker image from Docker Hub: `shoganator/waypoint:latest` or search for other specific pinned tag versions at https://hub.docker.com/r/shoganator/waypoint/tags

## Running

You should mount a directory to /data that will be used for the Waypoint database. Once started for the first time, you'll need to bootstrap the server.

See this blog post for more details: []().

## Build

To build yourself, simply clone this repository and build with `docker`. E.g.

`docker build -t waypoint .`
