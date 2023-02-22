# Ansible_deployment_via_docker

This project is about automating deployment on linux servers with Ubuntu 20.04LTS as an OS, by creating a jar archive with maven, building a custom docker image with it, uploading it to a remote docker repository(pre-build), and running it from remote docker engine server(pre-build), where a docker container is created for the application. The application is then tested with an API call.

Notes:
`inventory/group_vars/all/vault_variables.yaml` - variables with sensitive information, which are encrypted with ansible-vault

Requirements:


 `Apache Maven 3.6.3`
 
 
 `Docker version 20.10.22`
 
 
 `openjdk 18.0.2-ea 2022-07-19` 
 
 
