# Unit Testing Assignment

Unit Testing Assignment is a project build upon the Node and Typescript. The main purpose of this project is to create the playground for the unit testing learning. 

You have been assigned to a project as a Developer. You first task is to pass the project test cases.

# Basic Challenges

UT-001: Pass all the basic testing

```
npm run test:basics
```

Folder structure for basic challenges

```
|-src
    |-challenge-basics
        |-ch-[n]
            |-ch-[n].spec.ts
            |-ch-[n].ts
```

# Moderate Challenges

UT-002: Pass all the moderate testing

```
npm run test:moderate
```

Folder structure for basic challenges

```
|-src
    |-challenge-moderate
```

## Tech Stack

1. Typescript
2. Node
3. Express
4. PostgreSQL
5. Prisma (ORM)

## Installation and Running

1. Clone the repo.
2. Install the dependencies by running `npm install`.
3. Run `npm run prisma:migrate` to migrate schema.
4. Run `npm run prisma:generate` to install prisma client.

`npm run start:dev` start the server in development mode.
`npm run test:dev` to start Jest testing

## Database Migration and Setting

1. Run `npm run prisma:migrate` to migrate the prisma.schema.
2. Run `npm run prisma:generate` to update the prisma client with latest changes so that you get typechecking for latest changes to your schema.

Every time you make changes to `prisma/schema.prisma` make sure to run above commands.

For seeding run `npm run prisma:seed`
