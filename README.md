# Keycloak - Docker Compose

This repository contains a Keycloak instance on docker with docker compose. This
can be used in development and production. This repository is specifically meant
for the Errors Party website and intranet.

## Getting Started

1. Set up [dc-caddy](https://github.com/errorsparty/dc-caddy)

2. Clone the repository on your machine/server.

   ```sh
   git clone https://github.com/ErrorsParty/dc-keycloak /srv/dc-keycloak
   ```

3. Navigate into the directory.

   ```sh
   git clone cd /srv/dc-keycloak
   ```

4. Copy the environment example file.

   ```sh
   cp .env.example .env
   ```

5. Modify the environment file to your needs.

6. Start the keycloak instance.

   ```sh
   docker compose up -d
   ```

## Configuring Keycloak

> _Coming soon…_
