# Telegraf Machine Metrics

Simple setup to send machine metrics to Grafana Cloud.  
Clone, copy env, and run compose

1. `cp .env.sample .env`
2. Edit env var
3. `docker-compose up -d`

If having permission problem for docker:
```
sudo usermod -aG docker $USER
```