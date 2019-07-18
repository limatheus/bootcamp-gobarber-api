# GoBarber API

#### Bootcamp Rocketseat 2019

### Install dependencies

```
yarn
```

### Setup docker

docker run --name postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -dpostgres
docker run --name mongodb -p 27017:27017 -d -t mongo
docker run --name redis -p 6379:6379 -d -t redis:alpine

### Run Migrations

```
yarn sequelize db:migrate
```
