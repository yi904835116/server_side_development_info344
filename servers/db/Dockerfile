# Docker container image based on `mysql`
# with your `schema.sql` file copied into
# /docker-entrypoint-initdb.d/schema.sql
FROM mysql:5.7
COPY schema.sql /docker-entrypoint-initdb.d/schema.sql