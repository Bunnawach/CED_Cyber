# Cyber Security

## Information
- Bunnawach Bamrung
- Direk Puankum
- Kasidach Prabpal
- Sarawut Bunprakrong
- Kanokwan Pantang

## Environment

```sh
cp env.simple .env
```

## Running a services
### Database
```sh
docker compose -f docker-compose.yaml up # monitoring
docker compose -f docker-compose.yaml up -d # background


cp env.simple .env

```

### Admin
```sh

docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background


cp env.simple .env

=======
docker compose -f docker-compose.yaml up #monitoring
docker compose -f docker-compose.yaml up -d #background

```