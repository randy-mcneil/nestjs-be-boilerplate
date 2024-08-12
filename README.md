
## Description
Simple NestJS backend API implementation

## Installation

```bash
$ npm install
```

## Getting Started

### Install packages
```bash
$ npm install
```

### Environment Setup

- Copy `.env.example` as `.env` file

- Update the `DATABASE_HOST` in `.env` file to `localhost`.

  This is necessary to run dev server locally.

### Run the servers

```bash
$npm run docker:dev:up
```

### Run migration and seed initial users

```bash
$npm run migration:run
$npm run seed:run
```

### Start the dev server

```bash
$npm run start:dev
```

### Testing
```bash
$npm run test:e2e
```

## Technical Stack

- NestJS
- PostgreSQL + TypeORM
- JWT, Passport
- NestJS ConfigurationService
- NestJS ValidationPipe using `class-validator` and `class-transformer`
- Docker for DB server
- Repository Pattern for persistence
- Role based endpoint protection