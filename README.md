# Turborepo turbo config package starter

This is from a Turborepo starter maintained by the Turborepo core team. 

This example also shows how to use [Workspace Configurations](https://turbo.build/docs/core-concepts/monorepos/configuring-workspaces).

## What's inside?

This Turborepo common config repo includes the following packages:

### Packages
- `@devades/eslint-config`: ESLint configurations used throughout the monorepo
- `@devades/jest-presets`: Jest configurations
- `@devades/logger`: isomorphic logger (a small wrapper around console.log)
- `@devades/typescript-config`: tsconfig.json's used throughout the monorepo
- `@devades/tailwind-config`: tsconfig.json's used throughout the monorepo

Each package and app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Jest](https://jestjs.io) test runner for all things JavaScript
- [Prettier](https://prettier.io) for code formatting

## Check Out TurboRepo's Kitchen Sink Demo

Run the following command:

```sh
npx create-turbo@latest -e kitchen-sink
```

### Instructions for installing packages or releasing from command line to devades github organisation as lari-ks github user (Admin user on devades org)

#### github set email on repo (assuming user has multiple Github users on local machine)

```
git config user.email "email"
```

#### npm login for Github packages / Github npm registry

npm login --scope=@NAMESPACE --auth-type=legacy --registry=https://npm.pkg.github.com

```
npm login --registry=https://npm.pkg.github.com
lari-ks as username
new personal access token as password, added as secret to repo settings secrets
```

