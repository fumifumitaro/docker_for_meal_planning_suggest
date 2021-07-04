FROM mysql:8.0

ENV TZ=UTC

COPY ./my.cnf /etc/my.cnf

RUN set -eux && \
  mkdir /var/lib/mysql-files