# Example KeyClock securing ReactJS Application

The following project highlights securing a ReactJS App behind Keycloak.

## Requirements

* Docker for mac
* npm


## Quick start

On one terminal run KeyCloak
``` bash
# Keyclock instances
docker run -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin -e DB_VENDOR=H2 jboss/keycloak
```

On second terminal run example React app.
``` bash
# Install
npm install 

# Start web server
npm start
```

## Reference
* https://scalac.io/user-authentication-keycloak-1/
* https://scalac.io/user-authentication-keycloak-2/ (Not Implemented)

