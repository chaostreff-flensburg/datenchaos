# `/traefik` 
This directory contains the configuration for the træfik reverse proxy.

## Setup
If you want to use tls encryption, you need to create a file for the generated keys:
```bash
touch acme.json
# træfik demands that permissons of acme.json are set to 600 or else it won't start
chmod 600 acme.json
```
Now start the service with docker-compse:
```bash
# Start container in the background with -d flag
docker-compose up -d
```

---
Made with ♡ at [Chaostreff Flensburg](https://twitter.com/chaos_fl)
