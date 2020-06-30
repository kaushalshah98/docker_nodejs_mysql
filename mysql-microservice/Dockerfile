## Pull the mysql:5.7 image
FROM mysql:5.7

## The maintainer name and email
MAINTAINER Kaushal Shah <kaushalshah589@gmail.com>

# database = test and password for root = password
ENV MYSQL_DATABASE=docker \
    MYSQL_ROOT_PASSWORD=0168

# when container will be started, we'll have `test` database created with this schema
COPY ./test-dump.sql /docker-entrypoint-initdb.d/
