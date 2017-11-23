Just run:

```
docker-compose up -d
docker-compose scale web=10
docker-compose up -d --force-recreate --no-deps lb
```
