# Authentication and Authorization with NestJS

## Tools

- Visual Studio Code

## Extension Visual Studio Code

- Rapid API Client

## How to Use

1. Clone this repository
2. Make sure project folder already active at terminal / command line
3. Run `cp .env.example .env` and update database url
4. Run `npm install` to install dependency
5. Run `npx prisma db push` to migrate table
6. Run `npm run start:dev` to run project
7. Happy Hacking

## Endpoint list

| Route           | Method   | Description       |
| ----------------| -------- | ----------------- |
| /auth/login     | `POST`   | Login             |
| /auth/register  | `POST`   | Register          |
| /me             | `GET`    | Get user login    |

## Swagger

| Route    | Method | Description     |
| -------- | ------ | --------------- |
| /openapi | `GET`  | Show swagger UI |
