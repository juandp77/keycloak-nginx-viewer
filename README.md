# keycloak-nginx-viewer

## Run Locally

```
docker-compose up -d
```

The docker-compose.yml has a service called `keycloakutils` which will run once the actual keycloak server will start to create the OHIF reasm and test user automatically.

Please wait for roughly 30 seconds before accessing the below URLS:

OHIF: http://127.0.0.1
Orthans Explorer: http://127.0.0.1/pacs-admin

Keycloak Admin: http://127.0.0.1/aut/admin


