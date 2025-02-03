Docker Pastey for Cloud
========================
**Description:** Docker for Pastey

**Copyright:** 2023-2025 Fabio Castelli (Muflone) <muflone(at)muflone.com>

**License:** GPL-3+

**Source code:** https://github.com/muflone/docker-cloud-pastey/

**Documentation:** http://www.muflone.com/docker-containers/

System Requirements
-------------------

* Docker (tested using v.24.07)
* Docker compose (tested using v.2.23.1)

Installation
------------

Build the container using Docker compose with:

    docker-compose up -d

If you use Docker swarm you can use:

   docker stack deploy docker-cloud-pastey --compose-file docker-compose.yaml

