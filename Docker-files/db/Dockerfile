FROM mysql:8.0.33
LABEL "project"="vprofile"
LABEL "auther"="Omymaalkateeb"
ENV MYSQL_ROOT_PASSWORD ="vprofilepass"
ENV mysql_DATABASE="acounts"

ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql

EXPOSE 3306