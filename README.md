# Postgres setup
1. Have docker installed
2. Run the following command to start a postgres container
```bash
docker run --name pg_profile_db -p 5431:5432 -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=password -e POSTGRES_DB=postgres -d postgres:16.1
```

# Setup Instructions
1. Clone the repo
2. mvn install using the maven wrapper
3. Point datasource in application.properties to postgres alpine db
4. Run the application
