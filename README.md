- Create .env file
  - set POSTGRES_DB to database name
- docker-compose up
- knex migrate:latest
- node index.js

### Changes:
- POSTGRES_DB is now the name of the db to use.
- Connecting to the db can be done via:
 - using postbird: https://github.com/paxa/postbird
- knexfile and dotenv is used to declare credentials
