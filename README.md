# HomeMonitoring
Collect Data from Shelly with MQTT Events, store in database and visualize with grafana

Setup:
smarthome-monitoring/
├── docker-compose.yml
├── mosquitto/
│   └── config/
│       └── mosquitto.conf
├── telegraf/
│   └── telegraf.conf
└── grafana/
    ├── provisioning/
    │   ├── datasources/
    │   │   └── datasource.yml
    │   └── dashboards/
    │       └── dashboards.yml
    └── dashboards/
        └── shelly_dashboard.json
        

Please feel free to reach out for more Information.

