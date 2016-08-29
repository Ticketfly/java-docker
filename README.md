# Minified Docker image with Java 7

Inspired by the excellent [anapsix Docker Alpine Java](https://github.com/anapsix/docker-alpine-java) images.

Basic Docker [Alpine Linux](https://hub.docker.com/_/alpine/) image for running Java 7 applications, it is much smaller than the [official Java 7](https://hub.docker.com/_/java/) image (175 MB vs 420 MB) which is based on a Debian image.

### Usage

Example:

`docker run -it --rm ticketfly/java:7 java -version`