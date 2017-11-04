![Docker Pulls](https://img.shields.io/docker/pulls/holgerimbery/debian.svg)![Travis](https://img.shields.io/travis/holgerimbery/debian-multiarch.svg)
## debian-multiarch docker base image
debian multiarch docker base image

## usage 
```
docker pull holgerimbery/debian:latest
```

There is no need to specify your architecture during docker pull.
All images have qemu-user-static inside, if there is no need for it 
 
```
docker pull holgerimbery/debian:latest-slim
```

# arch
amd64, i386, arm64, armhf, ppc64el, s390x


# credits
based on ideas of the multiarch team https://github.com/multiarch, Phil Estes https://github.com/estesp/manifest-tool and inspired by Christy Perez https://github.com/docker/cli/pull/138

# git-repository
https://github.com/holgerimbery/debian-multiarch

## License
MIT (c) 2017 Holger Imbery https://github.com/holgerimbery

![made-in-berlin](https://github.com/holgerimbery/environment/raw/master/made-in-berlin-badge_small.png)
