First run
===

docker-compose up postgres

docker-compose up initdb

docker-compose up scheduler webserver

Normal run
===
docker-compose up postgres scheduler webserver


http://localhost:8080/
