# pdhp
The configuration setup to run all applications needs for pdhp stack

## INSTALL

`sudo apt-get install docker docker-compose`

or visit https://docs.docker.com/compose/install/

## RUN

`sudo docker-compose up db`

wait until the database are ready for connection, so, on another terminal, ...

`sudo docker-compose up create`

this will create and populate the database and finaly ...

`sudo docker-compose up web api`

open http://localhost:8080 and search for "*"



