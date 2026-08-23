Docker Alpine Systemd
=====================

This Dockerfile can build containers capable to use systemd.

Branches
--------

This repository has multiple tags that relate to Almalinux versions.

|Alpine Version|Docker image tag|
|---------------|--------------------|
| 3             | 3                  |
| edge          | edge               |

Manually starting
-----------------

```shell
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  mullholland/docker-alpine-systemd
```
