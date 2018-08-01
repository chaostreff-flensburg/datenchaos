# datenchaos
> 💾 a chaotic open data portal

This repo contains all the configuration and code for our open data portal and api. Each folder should contain a readme with the needed information to start  the service.

- [træfik](./traefik) (reverse proxy)
- [Prometheus](./prometheus) (data scrapper)
- [Grafana](./grafana) (monitoring & analytics)

## Setup
Clone the repo and create a docker network named `web`.
```
docker network create web
```

To run prometheus and grafana you have to adjust the folder permissions by applling
```
$ chmod -R 777 grafana/
$ chmod -R 777 prometheus/
```



In the root folder is one docker-compose.yml. This file contain all services ad configs wich are located in the service foldes.

---
Made with ♡ at [Chaostreff Flensburg](https://twitter.com/chaos_fl)
