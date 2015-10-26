# Mesos-Modules-Dev docker image.
Improved docker for building mesos modules. Tested as a base for building Serenity.

Dockerhub: [bplotka/mesos-modules-dev](https://hub.docker.com/r/bplotka/mesos-modules-dev/)

# Usage:
 Use this Dockerfile or just pull it from dockerhub:
  
```
    docker pull bplotka/mesos-modules-dev
```
# Improvement details:
Based on: [mesosphere/mesos-modules-dev](https://hub.docker.com/r/mesosphere/mesos-modules-dev/)

1. Clang compiler installed.
2. Vim editor installed.
3. Checkouted to different Mesos Version (using tags).
4. Increased multi-threading option in make.