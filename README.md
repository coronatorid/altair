# Altair

Altair open source API Gateway.

## How to Install & Run

1. Go to altair dir and then execute `docker-compose up`
2. Run the migration `docker run  --volume $(pwd):/opt/altair --entrypoint altair codefluence/altair migrate main_database`
3. Now altair is ready to go
