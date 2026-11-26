# NestJS HTTP service example

A small TypeScript project showing how a NestJS controller delegates to a service. The sample exposes a single `GET /` route and includes Jest and Supertest tests.

## Run locally

Use a Node.js version compatible with NestJS 11.

```bash
npm ci
npm run start:dev
curl http://localhost:3000/
```

## Tests and code

- `npm test` runs the unit tests. `npm run test:e2e` checks the HTTP endpoint.
- [Controller](src/app.controller.ts), [service](src/app.service.ts), and [HTTP test](test/app.e2e-spec.ts).

This example started from the [NestJS framework starter](https://github.com/nestjs/typescript-starter).
