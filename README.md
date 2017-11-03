## debian-multiarch docker image
debian multiarch docker image with manifest-file 
*playground for experimenting with multiarch deployments*

## usage 
docker pull holgerimbery/debian:latest
there is no need to specify your architecture
the images are qemu enabled, if there is no need for qemu enablement pull :latest-slim

# arch
amd64, i386, arm, armhf, ppc64el


# credits
based on ideas of the multiarch team https://github.com/multiarch, Phil Estes https://github.com/estesp/manifest-tool & Christy Perez https://github.com/docker/cli/pull/138
