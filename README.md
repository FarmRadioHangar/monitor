# monitor
Compose stack for metrics collection and visualization

Buuilds images for
- influxdb 1.0.0-beta2
- telegraf  1.0.0-beta1
- chronograf 0.13

# Usage
 Use docker compose to build
```bash
docker-compose build --force --no-cache
```

Then start the services in the background
```bash
docker-compose up -d
```
