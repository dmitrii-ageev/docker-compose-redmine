# docker-compose-redmine
Docker Compose file to run Redmine - project management web application.

## Getting started

Download Docker. If you are on Mac or Windows, Docker Compose will be automatically installed. If you're using Docker for Windows on Windows 10 pro or later, you must also switch to Linux containers.

To run Redmine with MySQL database, run in this directory:

` docker-compose --file docker-compose-mysql.yml up -d `

for PostgreSQL database, run:

` docker-compose --file docker-compose-postgresql.yml up -d `

The app will be running at http://localhost:80.

## Note

The database initialization on the first run might take up to 5 minutes!
