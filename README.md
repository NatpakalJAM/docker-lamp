# Docker LAMP

> my simple lamp stack docker using [mattrayner/lamp](https://hub.docker.com/r/mattrayner/lamp)

[![Build Status][shield-build-status]][info-build-status]
[![Docker Hub][shield-docker-hub]][info-docker-hub]
[![Quay Status][shield-quay]][info-quay]
[![License][shield-license]][info-license]

## Component

Component | `latest-1604-php7`
---|---
[Apache][apache] | `2.4.18`
[MySQL][mysql] | `5.7.23`
[PHP][php] | `7.2.9`
[phpMyAdmin][phpmyadmin] | `4.8.2`

## Quick Start

1. Start service

```
$ docker-compose up -d
```

2. Stop service

```
$ docker-compose down
```

[apache]: http://www.apache.org/
[mysql]: https://www.mysql.com/
[php]: http://php.net/
[phpmyadmin]: https://www.phpmyadmin.net/

[info-build-status]: https://circleci.com/gh/mattrayner/docker-lamp
[info-docker-hub]: https://hub.docker.com/r/mattrayner/lamp
[info-quay]: https://quay.io/repository/mattrayner/docker-lamp
[info-license]: LICENSE

[shield-build-status]: https://img.shields.io/circleci/project/mattrayner/docker-lamp.svg
[shield-docker-hub]: https://img.shields.io/badge/docker%20hub-mattrayner%2Flamp-brightgreen.svg
[shield-quay]: https://quay.io/repository/mattrayner/docker-lamp/status
[shield-license]: https://img.shields.io/badge/license-Apache%202.0-blue.svg