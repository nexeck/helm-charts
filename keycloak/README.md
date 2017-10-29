# Keycloak Chart

[Keycloak](http://www.keycloak.org/) is an open source, identity and access management.

## Chart Details
This chart will provision a fully functional and fully featured Keycloak installation.

PostgreSQL is used as the database for Keycloak state.

For more information on Keycloak and its capabilities, see it's [documentation](http://www.keycloak.org/documentation.html).

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm install --name my-release .
```

Note that this chart pulls in many different Docker images so can take a while to fully install.

## Configuration

Configurable values are documented in the `values.yaml`.

Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`.

Alternatively, a YAML file that specifies the values for the parameters can be provided while installing the chart. For example,

```bash
$ helm install --name my-release -f values.yaml .
```

> **Tip**: You can use the default [values.yaml](values.yaml)
