FROM mysql:8.0.33
LABEL "Author"="Rajesh"
LABEL "Project"="Vprofile"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

RUN db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql
