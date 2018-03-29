# elastic-docker

Prerequisites
Docker and Compose. Windows and Mac users get Compose installed automatically with Docker. Linux users can:
pip install docker-compose
At least 4GiB of RAM for the containers. Windows and Mac users must configure their Docker virtual machine to have more than the default 2 GiB of RAM:
Docker VM memory settings

Starting the stack
Try docker-compose up to create a demonstration Elastic Stack with Elasticsearch, Kibana, Logstash, Auditbeat, Metricbeat, Filebeat, Packetbeat, and Heartbeat.

Point a browser at http://localhost:5601 to see the results.

Log in with elastic / changeme.