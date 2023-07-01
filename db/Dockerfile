FROM mariadb:10.6.4-focal as db

COPY password.txt /var/password.txt

ENV MYSQL_DATABASE=example
ENV MYSQL_USER=root
ENV MARIADB_ROOT_PASSWORD="test-1234"

