# homeassistant_mqtt_grafana_influxdb
 
 Walkthrough of: https://diyi0t.com/home-assistant-mqtt-tutorial/
 
 For Docker:
 
 Installation of gafana and influxdb via Docker:  https://diyi0t.com/home-assistant-raspberry-pi-docker-setup/
 
 Followed by: https://diyi0t.com/visualize-mqtt-data-with-influxdb-and-grafana/
 
 How to set/edit influxdb user,database, configuration?
 
 Is this possible
 
 - via commands in a (Docker) terminal screen?
 - by editing config file(s) in external volume?
 - other?
 
The blog uses an MQTT "bridge" written in python. This bridge subscribes to MQTT messages sent by the ESP devices and sends the data to the influxdb database.
This bridge function could possibly be implemented in Nodered.


Influx Docker docs: https://github.com/docker-library/docs/blob/master/influxdb/README.md (docs in the Docker repository is not complete due to space limitations!)


Grafana contains a tutorial: https://grafana.com/tutorials/grafana-fundamentals/?utm_source=grafana_gettingstarted 
