# docker-socat


 [![Build Status](https://travis-ci.org/iJJi/docker-socat.svg?branch=master)](https://travis-ci.org/iJJi/docker-socat)

[socat](http://www.dest-unreach.org/socat/) tool in a docker container built on alpine linux so it's tiny!

It's on [docker-hub](https://hub.docker.com/r/fingershock/socat/) and [github](https://github.com/iJJi/docker-socat)

## tags and links

 * `latest`, [(Dockerfile)](https://github.com/iJJi/docker-socat/blob/master/Dockerfile) [![](https://images.microbadger.com/badges/image/fingershock/socat:latest.svg)](https://microbadger.com/images/fingershock/socat:latest "Get your own image badge on microbadger.com")

## running

Run any `socat` command.
```sh
docker run --rm fingershock/socat -u udp-recv:514 stdout
```

Get help for any commands
```sh
docker run --rm fingershock/socat -h
```

