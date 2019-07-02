## config database

```js
docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

```js
docker run --name mongodb -p 27017:27017 -d -t mongo
```

# Sequelize

para migrar as tabelas

```js
yarn sequelize db:migrate
```

```js
```

```js
```
