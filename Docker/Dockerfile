FROM mysql:latest

ENV MYSQL_RANDOM_ROOT_PASSWORD=yes

ENV MYSQL_DATABASE=deadline

ENV MYSQL_USER=MRTUser

ENV MYSQL_PASSWORD=ValFarScaner

ADD schema.sql /docker-entrypoint-initdb.d/

EXPOSE 3306