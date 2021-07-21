# hiam 
An SAML-2 Identity Provider (IdP)

## Build

To build without custom configurations, run `docker compose up`. 

This command will initialise and start the built-in LDAP service with default configurations. The LDAP service contains some dummy data, with which you can test out 
the IdP by sending HTTP requests to `localhost:445` for authentication and attributes query

## Configure

No interface available to configure the LDAP, you can manually change the configuration in the directory `/pkg/service/ldap`
