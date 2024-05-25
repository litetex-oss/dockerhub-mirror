[![DockerHub](https://img.shields.io/docker/pulls/litetex/homepage.svg?logo=docker&logoColor=white&color=blue)](https://hub.docker.com/r/litetex/homepage)
[![Mirror](https://github.com/litetex-oss/homepage-docker-mirror/actions/workflows/mirror.yml/badge.svg)](https://github.com/litetex-oss/homepage-docker-mirror/actions/workflows/mirror.yml)

# homepage-docker-mirror
DockerHub mirroring code for [gethomepage/homepage](https://github.com/gethomepage/homepage)

## Why?
``homepage`` is only hosted on GitHub Container registry (ghcr.io).

GitHub (including ghcr.io) still [doesn't support IPv6](https://github.com/orgs/community/discussions/10539) meaning it can't be pulled on IPv6 only hosts.

Related discussion: https://github.com/gethomepage/homepage/discussions/3527
