## Local setup
 - install Postgres
 - copy .env.local to .env
 - create user with psql: `CREATE USER sal WITH PASSWORD 'salpassword' CREATEDB;`
 - create local DB: `CREATE DATABASE sal WITH OWNER=sal;`
 - apply migration: `npx prisma migrate resolve --applied 0_init`

## Installation

```bash
$ pnpm install
```

## Running the app

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# production mode
$ pnpm run start:prod
```

## Test

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```