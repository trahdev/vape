# Vape

## Alloy development

Start the containerized development environment:

```sh
docker compose -f docker-compose.alloy.yaml up -d
```

The frontend listens on `http://localhost:3000`. Alloy proxies it at
`http://localhost:8080`.
