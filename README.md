# docker-compose-template

```
cp .env.example .env
```

edit .env

```
mkdir -p data/jail.d
```

```
cp jail.d/*.local data/jail.d/
```

```
docker-compose up -d
```

