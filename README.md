# Postgres Database Image

## 1 Overview
This project contains the Postgres Database Template. It uses only in development environment.

## 2 Developing locally 
Local development is done via a development docker image. As a minimum requirement, you need docker installed and a local clone of this repository.

> For information about install docker in your machine follow the next link :
> https://docs.docker.com/engine/installation/

### 2.1 Creating and running

#### 2.1.1 Using Docker Compose

The most simple way to build & run the MicroService is using Docker Composer, to this run the next command in the current folder **(repository root)**:

```docker-compose up```

#### 2.1.2 Authentication information

```user :  postgres```

```pass :  test1234```

> If you need change user data authentication go to **POSTGRES_PASSWORD=XXXXX** in docker-compose.yml


## General Document Helper Reference

#### Docker Cheat Sheet 

https://github.com/wsargent/docker-cheat-sheet
