FROM mysql:5.6

ENV MYSQL_ROOT_PASSWORD motdepasse
ENV MYSQL_DATABASE lutece

COPY ./sql-scripts/ /docker-entrypoint-initdb.d/
