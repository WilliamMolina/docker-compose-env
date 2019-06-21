# docker compose Environment variables
## Build image
docker build -t prueba .

## Default environment
docker-compose up

## Development environment
docker-compose -f docker-compose.dev.yml up

## Development environment
docker-compose -f docker-compose.prod.yml up

