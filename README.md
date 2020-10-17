# ansible-zabbix-java-gateway
Deploy docker container with zabbix java gateway based on official zabbix-java-gateway container (https://hub.docker.com/r/zabbix/zabbix-java-gateway).

## Role variables
| Variable | Default value | Description |
| :---:        |     :---:      |         :---: |  
service_name                    |       zabbix-jgw-docker                       |   Service name in OS
uninstall_service               |       false                                   |
docker_image                    |       zabbix/zabbix-java-gateway:latest       |   Docker image (https://hub.docker.com/r/zabbix/zabbix-java-gateway)

### How to use
    - installation: just start the role
    - uninstallation: add --extra-vars "uninstall_service=true"