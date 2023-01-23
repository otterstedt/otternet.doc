# SERVERS

## acer

id: 10

| Services        | Type    | Notes      |
|--------------   |:-----:  |:-----------:|
| [Home Assistant](https://github.com/otterstedt/otternet.conf/tree/master/hass/acer)  |  [docker](https://github.com/otterstedt/otternet.conf/tree/master/systemd/acer) |  |
| Grafana         |  apt    |            |
| Elastic Search  |  apt    |            |
| ffserver        |  [custom](https://github.com/otterstedt/otternet.conf/tree/master/systemd/acer) |  rtsp -> mjpeg          |
| motion          |  [custom](https://github.com/otterstedt/otternet.conf/tree/master/systemd/acer) |  cam 1-6   |
| iperf3          |  [custom](https://github.com/otterstedt/otternet.conf/tree/master/systemd/acer) |            |
| Node Exporter   |  custom |            |
| InfluxDB        |  apt    |            |
| ICT Tunnels     |  custom |            |

