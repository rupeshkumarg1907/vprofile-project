FROM mysql:8.0.33
LABEL "Project"="Vproject"
LABEL "Author"="Rupesh"

ENV MYSQL_ROOT_PASSWORD="vprojectpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql