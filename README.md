# monitor
Compose stack for metrics collection and visualization

Buuilds images for
- influxdb
- telegraf
- chronograf

# Usage
 Use docker compose to build
```bash
docker-compose build --force --no-cache
```

Then start the services in the background
```bash
docker-compose up -d
```
