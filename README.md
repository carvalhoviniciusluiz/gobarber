## config database

```js
docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

```js
docker run --name mongodb -p 27017:27017 -d -t mongo
```

```js
docker run --name redisbarber -p 6379:6379 -d -t redis:alpine
```

## sequelize

para migrar as tabelas

```js
yarn sequelize db:migrate
```

# mailtrap

necessita de uma conta no serviço para obter as variáveis de conexão

```js
https://mailtrap.io
```

# sentry

necessita de uma conta no serviço para obter as variáveis de conexão

```js
https://sentry.io
```
