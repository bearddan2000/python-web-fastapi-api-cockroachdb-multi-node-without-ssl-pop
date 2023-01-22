# python-web-fastapi-api-cockroachdb-multi-node-without-ssl-pop

## Description
Creates an api of `pop` for a fastapi project.

A python fastapi build, that connects to 3 node cluster
cockroach database without ssl.

## Tech stack
- python
  - fastapi
  - sqlalchemy
- bootstrap
- jquery
- dataTable
- cockroachdb

## Docker stack
- python:latest
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- Endpoints
  - [Select all](http://localhost/pop)
- [Master node webui](http://localhost:8000)
- [Slave node 1 webui](http://localhost:8001)
- [Slave node 2 webui](http://localhost:8002)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Cockroach setup](https://github.com/s0rg/cockroach-compose)
