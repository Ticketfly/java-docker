# Minified Docker image with Java 8

Inspired by the excellent [anapsix Docker Alpine Java](https://github.com/anapsix/docker-alpine-java) images.

Basic Docker [Alpine Linux](https://hub.docker.com/_/alpine/) image for running Java 8 applications, it is much smaller than the [official Java 8](https://hub.docker.com/_/java/) image which is based on a Debian image.

### Usage

Example:

`docker run -it --rm ticketfly/java:8 java -version`