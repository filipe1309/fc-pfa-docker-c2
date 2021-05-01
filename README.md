# <p align="center">PFA Docker (C2) 🐋</p>

<p align="center">
<img src="https://img.shields.io/badge/nodejs-15.0-green" alt="NodeJS"/>
</p>

## 💬 About

This project was developed following [FullCycle's PFA](https://portal.code.education/lms/#/180/164/128/conteudos?projeto=54&fase=253).

### Challenge 2

-   [x] Create a docker-compose.yaml with 3 services
-   [x] Create a mysql service with an official MySQL image
-   [x] MySQL service must not have a Dockerfile
-   [x] MySQL service must have a volume to persist on `dbdata` folder
-   [x] MySQL service must use `entrypoint-initdb.d` to create & populate db
-   [x] MySQL service must have a shrared network with App service (without Nginx)
-   [x] App service must list data from MySQL
-   [x] App service must verify MySQL service is ready before inicialization (Dockerize)
-   [x] App service must have a shrared network with Nginx service (without MySQL)
-   [x] Nginx service must reverso-proxy to the App
-   [x] Nginx service must expose porto 8000
-   [x] Nginx service must start after App service has been inicialize
-   [x] Nginx service must restart if App service has not been inicialize
-   [x] Nginx service must be restarted if the app service has not been started
-   [x] Project must run with a simple `docker-compose up`

## :computer: Technologies

-   [Docker](https://www.docker.com/)
-   [Docker Compose](https://docs.docker.com/compose/)
-   [Dockerize](https://github.com/jwilder/dockerize)
-   [Node.js](https://nodejs.org/en/)
-   [Nginx](https://www.nginx.com/)
-   [MySQL](https://www.mysql.com/)
-   [Node MySQL2](https://www.npmjs.com/package/mysql2)

## :scroll: Requirements

-   [Docker](https://www.docker.com/)
-   [Docker Compose](https://docs.docker.com/compose/)

## :cd: Installation

```sh
git clone git@github.com:filipe1309/fc-pfa-docker-c2.git
```

```sh
cd fc-pfa-docker-c2
```

## :runner: Running

```sh
docker-compose up
```

> docker-compose down to remove containers

Access http://localhost:8000/

## License

[MIT](https://choosealicense.com/licenses/mit/)

## About Me

<p align="center">
    <a style="font-weight: bold" href="https://www.linkedin.com/in/filipe1309/">
    <img style="border-radius:50%" width="100px; "src="https://avatars.githubusercontent.com/u/2081014?s=60&v=4"/>
    </a>
</p>

---

<p align="center">
    Done with ♥ by <a style="font-weight: bold" href="https://www.linkedin.com/in/filipe1309/">Filipe Leuch Bonfim</a> 🖖
</p>
