Just run:

```
docker-compose up -d
docker-compose escale web=10
docker-compose up -d --force-recreate --no-deps lb
```