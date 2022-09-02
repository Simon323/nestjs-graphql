<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Create new project

```bash
$ nest new my-app
```

## Monorepo / Microservices / Library

```bash
# Create new app in monorepo context
$ nest generate app your_app_name

# Create shared library
$ nest g library name_your_library
```

## NestJS cli

```bash
# generate controller
$ nest g controller users

# generate module
$ nest g module users

# generate service without tests
$ nest g service users --no-spec

# generate service
$ nest g service users
```

## Running the app

```bash
# development
$ yarn start

# watch mode
$ yarn start:dev

# production mode
$ yarn start:prod

# run another app from monorepo
$ yarn start:dev name_app_from_apps_directory
```

## Test

```bash
# unit tests
$ yarn test

# e2e tests
$ yarn test:e2e

# test coverage
$ yarn test:cov
```

## Run in docker

```bash
# first time
$ docker-compose up --build -V

# after
$ docker-compose up
```

## Docker Hot Reload

```bash
# Issue with hot reload in docker
$ "start:dev": "WATCHPACK_POLLING=true nest start --watch",
$ https://stackoverflow.com/a/72478714
```

## RabbitMQ

```bash
# RabbitMQ GUI
$ http://localhost:15672
$ username: guest
$ password guest
```

## Auth

```bash
# npm packages
- passport
- @nestjs/passport
- passport-local
- @types/passport-local
- bcrypt
- @types/bcrypt
- @nestjs/jwt
- passport-jwt
- @types/passport-jwt

# install
$ yarn add passport @nestjs/passport passport-local @types/passport-local bcrypt @types/bcrypt @nestjs/jwt passport-jwt @types/passport-jwt
```

# GraphQL

```bash
# npm packages
- @nestjs/graphql
- graphql-tools
- apollo-server-express
- graphql
- @nestjs/apollo

# install
$ yarn add @nestjs/graphql graphql-tools apollo-server-express graphql @nestjs/apollo
```

# .env

```bash
# use configuration service instead process.env
- @nestjs/config
- joi

# install
$ yarn add @nestjs/config joi
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
