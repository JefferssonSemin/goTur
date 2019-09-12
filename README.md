
</h1>

<p align="center">An API for barber appointment and scheduling.</p>

<p align="center">
# GoBarber API
</p>

<hr />

## Features

A Node.js API using express, with auth jwt and postgre integration!

- ⚡ **Express** — A web framework for Node
- 💾 **Sequelize** — SQL dialect ORM for Node.js
- 🍂 **Postgre** — document-based database
- 🔑 **Redis** — key-value data model
- ⌨️ **Yup** - Object schema validation
- 💖 **Lint** — ESlint/Prettier/Editor Config

## Dependencies

- [Node.js](https://nodejs.org/en/) 8.0.0 ou >
- [Yarn](https://yarnpkg.com/pt-BR/docs/install)
- [Docker](https://www.docker.com/)

## Prerequisites

_In the next few weeks, I plan to include Docker directly in the repository with docker-compose, until there this step is required._

To run this server you will need three containers running on your machine.

To do so, you will need to run the following commands:

- `docker run --name database -e POSTGRES_PASSWORD=docker -p 5433:5432 -d postgres`;

_obs: To start the container `docker start <container_id>` and if you are using S.O Windows will need to use host 192.168.99.100 instead of localhost to access for example a postbird.

## Getting started

1. Clone this repo using `https://github.com/JefferssonSemin/goBarber.git`
2. Move to the appropriate directory: `cd goBarber`.<br />
3. Run `yarn` to install dependencies.<br />
4. Copy the `.env.example` file and rename it to `.env`.<br/>
5. Add all the values for the environment variables.<br/>
6. Run `yarn start` and `yarn dev` to run the servers at `http://localhost:3333`.
