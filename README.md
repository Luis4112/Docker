# Docker Compose Lab

A multi-container lab environment running nginx and MariaDB, 
built to demonstrate core Docker and docker-compose concepts.

## Stack
- **nginx** — web server, exposed on port 80
- **mariadb** — database, internal network only

## Concepts Demonstrated
- Named volumes for data persistence across container restarts;
- Secret management via `.env` file.
- Health checks with dependency ordering — web waits for db to be ready.
- Port security — database not exposed to host.

## Objective

It's a neat tool. Being curious I'm just messing with it, see what it can do and learning the ins and outs of it.
