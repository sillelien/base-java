# base-alpine 

A simple but powerful Java base image, based on Alpine Linux with S6 as a process supervisor and dnsmasq both of which have extremely small footprints adding virtually no runtime overhead and a minimal filesystem overhead. Alas Java 8 adds a pretty large overhead.

This image aims to be a suitable base image for people who want to deploy Java containers to [Tutum](http://tutum.co).

[![](https://badge.imagelayers.io/vizzbuzz/base-java.svg)](https://imagelayers.io/?images=vizzbuzz/base-alpine:latest 'Get your own badge on imagelayers.io')

##Credits

Originally taken from https://github.com/just-containers/base-alpine credit to John Regan <john@jrjrtech.com> and https://github.com/frol/docker-alpine-oraclejdk8 

