# alpine-mariadb
## What is this ?

This repository provides everything you need to operate MariaDB database server packed in Alpine Linux Environment.

## Environment Variables
| ENV | DESC |
| --- | --- |
| MYSQL_ROOT_PASSWORD | Password for root user |
| MYSQL_USER | New user|
| MYSQL_PASSWORD | New user password|
| MYSQL_DATABASE | Database created in image startup|
| MYSQL_PORT | Desired server port|

## Run
```
docker run -d \
        -p 3306:3306 \
        -it tanigroup/alpine-mariadb
```
