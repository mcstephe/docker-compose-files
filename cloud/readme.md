# Cloud Docker-Compose Example

Docker-compose example for setting up a file sync and share service based on NextCloud and served with Caddy.

## Prerequisites

Install [Docker](https://www.docker.com/) on your system.

* [Install instructions](https://docs.docker.com/installation/mac/) for Mac OS X
* [Install instructions](https://docs.docker.com/installation/ubuntulinux/) for Ubuntu Linux
* [Install instructions](https://docs.docker.com/installation/) for other platforms

Install [Docker Compose](http://docs.docker.com/compose/) on your system.

* Python/pip: `sudo pip install -U docker-compose`
* Other: ``curl -L https://github.com/docker/compose/releases/download/1.1.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose; chmod +x /usr/local/bin/docker-compose``

## Setup

Run `docker-compose build`. It will

* install caddy and nextcloud
* expose ports 443

## Start

Run `docker-compose up` to create and start caddy and nextcloud containers. The app should then be running on your docker daemon on ports 443

Refer to the references section for setup instructions for each app.

## Architecture

*Insert here*

## References

- https://caddyserver.com
- https://nextcloud.com
