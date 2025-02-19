# (Odyssey Course) Intro to GraphQL with TypeScript

Welcome to the starter code for **Intro to GraphQL with TypeScript**. You can find the [course lessons and instructions](https://apollographql.com/tutorials/intro-typescript) on Odyssey, [Apollo](https://apollographql.com)'s learning platform.

## How to use this repo

The course will walk you step by step on what to do. This codebase is the starting point of your journey!

Navigate to the root of the project directory, and run the following commands.

```
npm install && npm run dev
```

The `final` branch of this repo contains the final stage of the course, with all of the steps and code completed! If you get stuck, you can refer to it and compare your code.

## Getting help

This repo is _not regularly monitored_.

For any issues or problems concerning the course content, please refer to the [Odyssey topic in our community forums](https://community.apollographql.com/tags/c/help/6/odyssey). You can also [join the Apollo Discord](https://discord.gg/graphos).

## Reference documentation

For further reference, please consider the following sections:

-   [Official TypeScript documentation](https://www.typescriptlang.org/docs/)

## Adding server dependencies

To get started with our server, we'll need a couple packages first: @apollo/server, graphql and graphql-tag.

-   The @apollo/server package provides a full-fledged, spec-compliant GraphQL server.
-   The graphql package provides the core logic for parsing and validating GraphQL queries.
-   The graphql-tag package provides the gql template literal that we'll use in a moment.

In a new terminal in the root of the project, run the following:

```
npm install @apollo/server graphql graphql-tag
```

These packages are responsible for all of the GraphQL wiring we'll need to get our project up and running.
