# Keycloak StrataGem Theme

Keycloak provides theme support for web pages and emails. This allows customizing the look and feel of end-user facing pages so they can be integrated with your applications. Follow the Keycloak guidance here [Creating a Theme](https://www.keycloak.org/docs/4.8/server_development/#creating-a-theme)

**Note: this project structure was sampled from the [Keycloak Examples](https://github.com/keycloak/keycloak/tree/master/examples/themes)**

## Build

The project is setup to use maven for building the theme archive. Execute the following command to build the theme archive.

```bash
    mvn clean package
```

The theme archive will be created in this path `target/strataGem.jar`

## Deploy

To deploy the theme archive to keycloak, copy the `target/strataGem.jar` to the `$KEYCLOAK/standalone/deployments`
