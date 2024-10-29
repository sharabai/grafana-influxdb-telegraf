# Grafana InfluxDB Telegraf

## Description

This project automates the installation and configuration of Telegraf on Linux servers with config to send data to InfluxDB, which in turn is being used by Grafana for data vizualization. Grafana and InfluxDB are run using Docker Compose. The Grafana and InfluxDB still require to be manually connected. Telegraf collects basic system metrics (CPU, memory, disk, network, etc.)

## Defaults

Change influx_token in defaults/main.yml to the token generated with write permissions to the appropriate bucket

## License

This project is licensed under a custom restrictive license. All rights are reserved. You may not use, modify, or redistribute this code without explicit permission. Use by automated systems, including AI, is strictly prohibited.

For more details, refer to the [LICENSE](./LICENSE) file.
