# cedar-docker-keycloak-postgres-import
Keycloak with Postgres - Import CEDAR realm

The content is based on:

## Building and pushing to DockerHub:

````
docker build -t cedar-keycloak-postgres-import .

docker login

docker tag cedar-keycloak-postgres-import metadatacenter/cedar-keycloak-postgres-import:0.1.0
docker push metadatacenter/cedar-keycloak-postgres-import:0.1.0

docker tag cedar-keycloak-postgres-import metadatacenter/cedar-keycloak-postgres-import:latest
docker push metadatacenter/cedar-keycloak-postgres-import:latest
````