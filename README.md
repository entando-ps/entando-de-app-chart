# Entando de-app Helm Chart

This repository contains the prototype of an helm chart that can be used to install a standalone Entando de-app instance.

The project was started for a specific use case so it will most certain need some tweaks to work correctly in other environments or projects.

These are some requirements for the installation:
* A keycloak instance with a configured realm and client
* One ore two databases with the corresponding users (with enough grants to be able to create tables)
* A secret with the TLS data for the ingress already installed in the namespace
* An optional redis instance or cluster
