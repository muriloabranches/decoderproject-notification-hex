<h3>Create a PostgreSQL instance with Docker:</h3>

```console
docker run --name ead-notification-hex -e POSTGRES_PASSWORD=notification -e POSTGRES_USER=notification -e POSTGRES_DB=ead-notification-hex -p 5435:5432 -d postgres
