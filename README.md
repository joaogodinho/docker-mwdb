# docker-mwdb
Simple docker setup to spin the mwdb framework

Example content of `env/` files:

```
# env/mwdb-vars.env
MWDB_POSTGRES_URI=postgresql://mwdb:<postgres password>@postgres/mwdb
MWDB_SECRET_KEY=<random secret key>
MWDB_ADMIN_LOGIN=admin
MWDB_ADMIN_EMAIL=admin@localhost
MWDB_ADMIN_PASSWORD=admin
MWDB_BASE_URL=http://127.0.0.1
UWSGI_PROCESSES=5

# To enable plugins:
# MWDB_PLUGINS=<plugin name>
```

```
# env/postgres-vars.env

POSTGRES_USER=mwdb
POSTGRES_DB=mwdb
POSTGRES_PASSWORD=<postgres password>
```