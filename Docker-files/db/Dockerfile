FROM mysql:8.0.33
LABEL "project"="vprofile"
LABEL "Author"="Aslam"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql dokcer-entrypoint-initdb.d/db.backup.sql
