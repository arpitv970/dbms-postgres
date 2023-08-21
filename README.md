# About Project
This project is developed soley for learning purpose of mine for exploring `RDBMS` databases & `SQL` which could be very useful to me in various ways, especially while contributing to **Open-Source** projects such as *Cal.com*.

## Main focus of this project
- Get comfortable with `SQL` to access **DB**.
- Working with `PostgresSQL`.
- Integrate `PostgresSQL` in simpler projects using `Node.js` + `Express.js` as **backend frameworks** (*Next.js*)
- Able to contribute to nice **Open-Source** projects!

# TODO's
- Create Docker Environment to setup Postgres upon
    - [x] Create new Docker Network `dbms-network`
    - [x] Pull docker image of `Postgres`
    - [ ] SetUp `PGAdmin` for *GUI* of DB

## Docker commands:
### For `postgres`:
```bash
docker run -d \
-p 5432:5432 \
-e POSTGRES_PASSWORD=password \
--name postgresDB \
--net dbms-network \
postgres
```
### For `PGAdmin`:
```bash
docker run --rm \
-p 5049:5050 \
--name pgAdmin \
--net dbms-network \
thajeztah/pgadmin3
```
# References 
- [Postgres + Docker](https://www.commandprompt.com/education/how-to-create-a-postgresql-database-in-docker/)
- [Postgres + PGAdmin + Docker](https://dev.to/shree_j/how-to-install-and-run-psql-using-docker-41j2) 
