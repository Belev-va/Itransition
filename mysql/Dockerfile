FROM ubuntu:18.04

RUN apt update && apt install -y software-properties-common

RUN apt update && apt install -y mysql-server

EXPOSE 3306

RUN usermod -d /var/lib/mysql/ mysql

ENTRYPOINT ["service", "mysql", "start"]

CMD ["mysqld"]
