# harsh_docker_postgres
A repo for harsh

# Install the docker compose
docker-compose up -d redis postgres

docker-compose up -d superset

docker-compose exec superset superset-demo


# login into postgres container and look at your postgres db
docker exec -it postgresql_postgres_1 bash

psql -U superset

