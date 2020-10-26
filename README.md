# Testing npm7 with Lerna

## Findings

Lerna (at v3.22.1) still don't have any integration with `npm@7`, some commands like `lerna run` and `lerna exec` asks for **Yarn** configuration.

Also running `npm install` on root is only installing dependencies on root and `@scope/packages-a`.

## Usage?

```sh
$ npm install
$ cd packages/package-a
$ node ./index.js
```
