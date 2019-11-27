# HTPC Docker-Compose-Files

This pulls together several docker images to setup automated PVR and streaming service using

- Radarr
  - Automated movie PVR
- Sonarr
  - Automated television PVR
- Sabnzbd
  - Usenet downloader
- Lidarr
  - Automated music PVR

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

* installs containers
* expose ports 5050, 8989, 8080, and 32400

## Start

Run `docker-compose up` to create and start containers. The app should then be running on your docker daemon on ports 5050, 8989, 8080, and 32400

Refer to the references section for setup instructions for each app.

## Architecture

*Insert here*

## References

- https://couchpota.to/
- https://sonarr.tv/
- https://sabnzbd.org/
- https://plex.tv
