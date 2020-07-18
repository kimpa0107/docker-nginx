# Nginx with Docker composer

1. Copy `docker-compose.yml.bak` file to `docker-compose.yml`

```bash
cp docker-compose.yml.bak docker-compose.yml
```

2. Create nginx server config file in `nginx/conf.d` directory.


3. Create and start nginx docker container

```bash
docker-compose up -d
```

