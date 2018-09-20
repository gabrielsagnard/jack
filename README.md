# Traefik

Un projet qui montre comment exécuter plusieurs applications sur un serveur en utilisant Docker et Traefik.

## Dev setup

- Clone/download this repo
- Install Docker and Docker Compose
- Run `docker-compose up` in project root

## Prod setup
- Provision a server
- Configure a domain (and sub-domains) for your server
- Install Git
- Fork and clone this repo
- Install Docker and Docker Compose
- Edit *docker-compose.prod.yml* and *traefik.toml* as appropriate (domain and email)
- Create a *.htpasswd* file in */traefik* with credentials to access the Traefik dashboard
- Run `docker-compose -f docker-compose.prod.yml up --build -d` in project root
