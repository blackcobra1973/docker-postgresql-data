docker-postgresql-data
======================

Dockerfile to build persistent data container for PostgreSQL on CentOS 7

Setup
-----

To build the image

    # docker build --rm -t docker-postgresql-data .

Launching PostgreSQL
--------------------

#### Quick Start

    # docker run --name pgdata docker-postgresql-data
