Lesson:

Backend Course

Learn everything about backend web development: Golang, Postgres, Redis, Gin, gRPC, Docker, Kubernetes, AWS, CI/CD

- How to write and run database migration in Golang:
https://github.com/golang-migrate/migrate

Ref installation: https://www.geeksforgeeks.org/how-to-install-golang-migrate-on-ubuntu/

Step by step:

-- mkdir -p simple_bank directory

-- mkdir -p db/migration

-- migrate create -ext sql -dir db/migration -seq init_schema

> 2 migration files have been generated for us. Why ?

> Well, basically it’s a best practice when writing database migration.
The up-script is run to make a forward change to the schema.
And the down-script is run if we want to revert the change made by the up-script.
So when we run “migrate up” command,
The up-script files inside “db/migration” folder
will be run sequentially by the order of their prefix version.
On the contrary,
When we run “migrate down” command,
The down-script files inside “db/migration” folder
Will be run sequentially by the reverse order of their prefix version.

-- copy simple_bank.sql into init_schema.up.sql and drop all tables in init_schema.down


"COMPARATION BETWEEN SQLs"
![Alt text](/document/comparation_sql.png)