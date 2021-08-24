ARG MARIADB_VERSION=latest

FROM mariadb:${MARIADB_VERSION}

COPY my.cnf /etc/mysql/conf.d/my.conf

RUN chmod -R 644 /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]

EXPOSE 3306