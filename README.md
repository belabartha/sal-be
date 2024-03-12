## Local setup
 - install Postgres
 - create user with psql: `CREATE USER sal WITH PASSWORD 'S@lStr0ng0n3' CREATEDB;`
 - create local DB: `CREATE DATABASE sal WITH OWNER=sal;`

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