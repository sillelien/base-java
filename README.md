# base-java 

A simple but powerful Java base image, based on Alpine Linux with S6 as a process supervisor and dnsmasq both of which have extremely small footprints adding virtually no runtime overhead and a minimal filesystem overhead. Alas Java 8 adds a pretty large overhead.

This image aims to be a suitable base image for people who want to deploy Java containers to [Tutum](http://tutum.co).

[![](https://badge.imagelayers.io/vizzbuzz/base-java.svg)](https://imagelayers.io/?images=vizzbuzz/base-java:latest 'Get your own badge on imagelayers.io')

##Credits

Originally taken from https://github.com/just-containers/base-alpine credit to John Regan <john@jrjrtech.com> and https://github.com/frol/docker-alpine-oraclejdk8 


##License

This work is released under the ASL v2.0 with work from:

https://github.com/frol/docker-alpine-oraclejdk8 as MIT

The MIT License (MIT)

Copyright (c) 2015 Vlad

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

