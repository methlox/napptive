# Keycloak
</br>

<img src="https://www.keycloak.org/resources/images/screen-login.png" alt="drawing" width="600"/>

Keycloak is a Open Source Identity and Access Management.

[![Update Keycloak in to Napptive Playground](https://github.com/davma-io-templates/napptive-template/actions/workflows/keycloak-actions.yml/badge.svg)](https://github.com/davma-io-templates/napptive-template/actions/workflows/keycloak-actions.yml)

## How to access to Keycloak

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the keycloak component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open keycloak
```

The keycloak instance automatically gets a public URL in the form of:
```
https://keycloak-<active-namespace>.apps.playground.napptive.dev/admin/master/console
```
You can get the full link in endpoints inside component keycloak.

## Admin user and first login
The default credentials are:
- User: admin
- Password: admin


## References
* https://www.keycloak.org/
* https://www.keycloak.org/documentation
</br>
</br>
</br>