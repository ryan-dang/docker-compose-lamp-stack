FROM mysql:latest
COPY ./my.cnf /etc/mysql/conf.d/

ADD ./data.sql /docker-entrypoint-initdb.d

EXPOSE 3306
