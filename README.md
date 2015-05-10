# neo4j-ubuntu
This Dockerfile creates an ubuntu image with Neo4j installed inside.

## Use neo4j-ubuntu docker image

* Execute this command to download dockerhub image.

`docker pull telco2011/neo4j:[VERSION]`

* Or create container with bash access.

`docker run --name neo4j-bash -i -t telco2011/neo4j-ubuntu:[VERSION] /bin/bash`


##VERSIONS
* empty(latest): latest ubuntu with latest neo4j version 
* 14.10neo4j2.2.1: ubuntu 14.10 with Neo4j2.2.1