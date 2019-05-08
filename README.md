# Docker LAMP Stack

> my simple lamp stack docker

[![License][shield-license]][info-license]

## Component

Component | `LAMP`
---|---
[Apache][apache] | `Apache2`
[MariaDB][mariadb] | `10.4-bionic` / `10.4.4`
[PHP][php] | `7-apache` / `7.3.5`
[phpMyAdmin][phpmyadmin] | `latest`

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
[mariadb]: https://mariadb.org/
[php]: http://php.net/
[phpmyadmin]: https://www.phpmyadmin.net/

[info-license]: LICENSE

[shield-license]: https://img.shields.io/badge/license-Apache%202.0-blue.svg