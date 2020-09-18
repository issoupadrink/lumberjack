# Lumberjack

A docker cluster to store and visualise system metrics and logs in a time series database (InfluxDB) using the TICK stack. Launch the cluster with `docker-compose up -d` and access Chronograf on `localhost:8888`. If you want to change the metrics or logs consumed, update the `telegraf.conf` file. More info on this can be found [here](https://docs.influxdata.com/telegraf/v1.15/administration/configuration/).

You will need to download `rsyslog` to poll `syslogs`, if you wish to do this. 

![Image of Chronograf Dashboard](https://github.com/issoupadrink/lumberjack/blob/master/dashboard_example.png)
