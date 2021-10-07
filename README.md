# home-book-typescript-library-template

Home Book Typescript Library Template is prepared library template to create set of services or types for front-end & back-end.

## Table of Contents

- [Installation](#Installation)
- [Public-NPM](#Public-NPM)
- [Instruction](#InstructionM)
- [Libraries](#Libraries)

## Installation

```
npm install or npm i
```

## Public NPM

Before publish you have to bump up package.json version & change description in README.md which is use in npm as description. Last thing wchich you have to do is change name with prefix home-book-manager-{name}.

```
npm run build:publish
```

## Instruction

Before commit are call actions:

- branch name lint
- eslint ts
- prettier
- unit test
- commit syntax

If you need skip tests, after the commit message you have to put command:

```
git commit -m "<message>" --no-verify
```

## Libraries

- lodash - https://lodash.com/docs/4.17.15
- jest - https://basarat.gitbook.io/typescript/intro-1/jest
- prettier - https://prettier.io/
- eslint - https://eslint.org/
- husky - https://github.com/typicode/husky
- commit-lint - https://commitlint.js.org/#/
- branch-lint - https://github.com/barzik/branch-name-lint
