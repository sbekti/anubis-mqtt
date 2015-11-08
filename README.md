# anubis-mqtt
Dockerfile and configuration files for running Anubis MQTT server

### Docker Options

    -p 1883:1883
    -v /srv/mqtt/users:/mqtt/users
    -v /srv/mqtt/log:/mqtt/log
    -v /srv/mqtt/data/:/mqtt/data
