# Owncloud

## About

This is the docker compose file for making Owncloud run inside docker container. It will also set up MariaDB.

## Usage

Type: ```docker-compose up```

Browse to http://localhost:8000/

In the start-up screen select "Storage & Database" by clicking its arrow, select "MySQL/MariaDB" tab and write your database settings there.

You can find your settings in docker-compose.yml file.

**NOTE!** Database host must be changed to text *db*