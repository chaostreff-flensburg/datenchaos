# datenchaos
> 💾 a chaotic open data portal

This repo contains all the configuration and code for our open data portal and api. Each folder should contain a readme with the needed config files to start the service.

- [træfik](./traefik) (reverse proxy)
- [Prometheus](./prometheus) (data scrapper)
- [Grafana](./grafana) (monitoring & analytics)

## Setup
Clone the repo and create a docker network named `web`.

In the root folder is one docker-compose.yml. This file contain all services ad configs wich are locatet in the service foldes.

---
Made with ♡ at [Chaostreff Flensburg](https://twitter.com/chaos_fl)
