# homeLAB monitoring (tig) stack

## Mapped Ports

```
Host		Container		Service

3000		3000			  grafana
3003		3003			  grafana
8086		8086		    influxdb
8125		8125			  telegraf
6514    6514        telegraf > syslog
```

## Usefull Links

- https://towardsdatascience.com/get-system-metrics-for-5-min-with-docker-telegraf-influxdb-and-grafana-97cfd957f0ac
