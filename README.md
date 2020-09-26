# Journal de bord Authorization Server
This Spring Boot application is embedding a Keycloak server. It is intended to be use in the context of the "Journal de bord" project. An embedded Keycloak server makes it easy to start-up a pre-configured Keycloak server.

Its content come from the tutorial available on Baeldung website. You can read it [here](https://www.baeldung.com/keycloak-embedded-in-spring-boot-app).

## Authorization Server
The server issuing access tokens to the client after successfully authenticating the resource owner and obtaining authorization.

## Keycloak
Keycloak is an open-source Identity and Access Management solution administered by RedHat, and developed in Java by JBoss.
In this tutorial, we'll learn how to set up a Keycloak server embedded in a Spring Boot application.

Keycloak can also be run as a standalone server, but then it involves downloading it and setup via the Admin Console.