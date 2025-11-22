# traefik-testapp-2

## Getting started

### Setup `jedi-traefik`

Ensure you've set up the `jedi-traefik` service from
the [jedi-traefik](https://github.com/sajadtorkamani/jedi-traefik/tree/master)
project.

If you see the Traefik admin dashboard at http://localhost:8080, you should be
setup.

### Setup env variables

Copy `.env` to `.env.local` and set all values.

```shell
cp .env.example .env
```

### Start services

```shell
docker compose up -d
```

Access https://traefik-testapp-2.localhost and you should see a success message.
