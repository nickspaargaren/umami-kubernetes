## Add database tables to the database if the volume is exploded:

- kubectl exec -it [pod] -- sh
- psql -d postgresdb -U admin -W
- \c postgresdb
- paste sql script from [./sql/schema.postgresql.sql](https://github.com/umami-software/umami/blob/master/sql/schema.postgresql.sql)
- \dt
