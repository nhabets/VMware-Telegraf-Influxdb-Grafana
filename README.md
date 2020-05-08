# VMware-Telegraf-Influxdb-Grafana
Vsphere Monitoring by Telegraf Grafana Docker-Compose

Read :
https://grafana.com/grafana/dashboards/8159


# Installtion :

``` 
- Git clone https://github.com/shaybenb/VMware-Telegraf-Influxdb-Grafana.git
- docker-compose -f "docker-compose.yml" up -d --build

```

# Edit vsphere-stats.conf with your vsphere setting

``` 
 vcenters = [ "https://hostname.domain.com/sdk" ]
    username = "user@domain.com"
    password = "Password"

```
![Image description](https://www.jorgedelacruz.es/wp-content/uploads/2020/01/vsphere-grafana-summaries.png)

