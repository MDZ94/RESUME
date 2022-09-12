# KEYCLOAK AUTHORISATION APPLICATION

## The aim of this project:

The aim of creation this project is to create simple Frontend application with Angular, which will enable loggign with Keycloak identity broker.

## Technologies used in the project

### This project was generated with [Angular CLI]

### In the project, there is alredy set configuration to log in to the application with use of Keycloak identity broker with configuration in keycloak.config.js 

## Setting up project 

### STEP 1

Clone repository

### STEP 2 - Installation of Required Depedencies

npm - install

### STEP 3 - Keycloak Download and RUN

https://www.keycloak.org/downloads

### STEP 4 - Keycloak setup and configuration

https://www.keycloak.org/getting-started/getting-started-zip

### STEP 5 - Keycloak Server Configuration set up in Angular App

```
import { KeycloakConfig } from 'keycloak-js';

const keycloakConfig: KeycloakConfig = {
  url: '??????',
  realm: '????',
  clientId: '????',
};
```

### STEP 6- Integration Okta with Keycloak 

https://ultimatesecurity.pro/post/okta-saml/


