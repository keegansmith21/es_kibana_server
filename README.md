# es_kibana_server
Creating an Elasticsearch/Kibana HTTPS server with Docker Compose and Keycloak

# Building the server
Create the certificates and certificate authority (CA) using the create_certs.yml as a docker-compose file  
```docker-compose -f create_certs.yml run --rm create_certs```  
Build the Elasticsearch, Kibana, Keycloak and Postres containers

