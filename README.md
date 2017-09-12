# docker-monitoring
Setup Cadvisor - Influxdb - Grafana to monitor all container in swarm
## Architecture

![architechture](https://github.com/cuongnb14/docker-monitoring/raw/master/architecture.png)

## Step
1. Run `docker stack deploy --compose-file=docker-compose.yml monitoring`
2. Create database `cadvisor` in influxdb
3. Access grafana web and config database source
4. Import dashboard id: 1367
