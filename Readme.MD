# Keycloak 17.0.1 Docker compose example

- Add `host.docker.internal` to your hosts file

- Start postgres container

```sh
cd postgres
docker-compose up -d
```
- Create a database called `keycloak_postgres`

- Start keycloak container

```sh
cd keycloak
docker-compose up -d
```

- Access [https://localhost:8099](https://localhost:8099)
