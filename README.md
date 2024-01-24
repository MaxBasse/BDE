# Benchmark BkA100

This is the repository for the BDE's website.
This repo contains the website and the games files, a PostreSQL database is required for scoreboard.
Get a local copy of this repo and follow these simple steps.

## Running the website

1. ### Set up a PSQL database
   
   This database may be local or external.

1. ### Set up the config.json

Before running the website, you must specify some information in the `config.json` file.

```json 
{  
    "host": "localhost",  ## Or your db address if you're not using a local db
    "password": "1234",  ## Db's password 
    "database": "BDE",   ## Database's name
    "user": "postgres",  ## User let it to postgres
    "port": 5432  ## Port of the db 
}
```
