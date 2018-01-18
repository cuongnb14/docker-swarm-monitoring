# docker-swarm-monitoring
Setup Cadvisor - Influxdb - Grafana to monitor all container in swarm
## Architecture:

![architechture](https://github.com/cuongnb14/docker-monitoring/raw/master/architecture.png)

## Step:
1. Run `docker stack deploy --compose-file=docker-compose.yml monitoring`
2. Access grafana web and config database source
3. Import dashboard id: 1367 (See: https://grafana.com/dashboards/1367)

## Demo:
![Demo](https://github.com/cuongnb14/docker-monitoring/raw/master/Grafana_Docker_Swarm_Dashboard.png)

