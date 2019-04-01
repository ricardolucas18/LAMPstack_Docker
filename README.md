# LAMPstack_Docker

This project was made to improve my skills about docker and containers.

### Installation and documentation


In order to run this stack you'll need docker and docker-compose installed:

Docker:
* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

Docker-compose:
* Full documentation is available on [Docker's website](https://docs.docker.com/compose/).
* Code repository for Compose is on [GitHub](https://github.com/docker/compose).
* If you find any problems please fill out an [issue](https://github.com/docker/compose/issues/new/choose).

### Run this project using docker

Run these commands in the same directory ad docker-compose.yml .

Build Services:
```
 docker-compose build
```

Start and run the entire project:
```
 docker-compose up
```
### Create Database and execute .sql file in  sql folder
After the project is running open your browser and go to localhost:8000

Log in using these credentials:

Username: root
Password: password

Create a new database called 'db'.

Select this new data base created and import the .sql file that is in sql folder to create the table with entries.

### Available Services

phpmyadmin:
```
 localhost:8000
```
Username: root
Password: password

Apache with php:
```
 localhost:8001
```

MailHog:
```
 localhost:8002
```


