# Movies App

## Description

Example project of the consumption of an API, using React, TypeScript, SCSS Module and Docker.

- Problems found:

  - CORS - Resolved using proxy in package.json

## Dependencies

- Node.js 10+

## Development

1. `npm install`
2. `npm start`

## Running the project on Docker

1. `docker build -t movies-app .`
1. `docker run -p 3000:3000 -d movies-app`

## Running tests

- `npm run test`

## Scripts

- `start` - Starts development server
- `build` - Builds the application assets for production
- `test` - Runs all unit tests
- `lint` - Run lint
