# JS Planet defense game

![Pre Build Checks](https://github.com/dentisfy/dentisfy-application/workflows/Pre%20Build%20Checks/badge.svg)
![Deploy to Production](https://github.com/dentisfy/dentisfy-application/workflows/Deploy%20to%20Production/badge.svg)

**Production:** https://app.dentisfy.com

**Staging:** https://app-staging-dentisfy.com

## Getting started

```
  git clone https://github.com/dentisfy/dentisfy-application.git

  cd dentisfy-application

  npm install
```

You'll be able to start the project using your local database or staging environment:

```
  // local backend and database
  npm start

  // staging backend and database
  npm run start-dev
```

See http://localhost:3000/.

### Environment variables

See `.env.example` file to see where to add the variables.

## Code quality

Linting

```
  npm run lint
```

Tests

```
  npm run test
```

## Translations

Extract messages

```
  npm run i18n-extract-messages
```

Manage messages

```
  npm run i18n-manage
```

## Pre Push

You can run code quality and translations at once by running:

```
npm run prepush
```
