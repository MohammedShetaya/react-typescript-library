# react-typescript-library-template

## Install

### Github Users

Since this is a `template repository`, you can use that green `Use this template` button to start a new repository from this template.

### Non-Github Users

Clone the repository:

```
git clone --depth 1 git@github.com:alioguzhan/react-typescript-library-template.git
```

Install the deps:

```bash
yarn install
```

If you want to change or remove some parts of this template, do it before start development.
Once you feel ready, remove the `.git` folder and start a new one:

```
rm -rf .git && git init
```

> You can check if there are any outdated package with [npm-check-updates](https://www.npmjs.com/package/npm-check-updates) tool.

## Development

Write your library code to `src/index.tsx` file and run:

```
yarn start
```

This will watch your changes and reloads the server.

### Commit Messages

This setup expects you to follow conventional-commits format. There is a husky command runs before every commit for validation.

To learn more about conventional commits see [its website](https://www.conventionalcommits.org/en/v1.0.0/).

You can remove that section from `package.json` also remove the related package(s):

```
yarn remove -D @commitlint/cli
```

## Build

Run:

```
yarn build
```

This will create your compiled files under `./dist` folder. And generates a documentation with `TypeDoc` under `./docs` folder.

## Test

Jest is configured and ready to use. Just run:

```
yarn test
```

## Docs

This template uses [TypeDoc](https://typedoc.org/) by default.

Run `yarn make:docs` and a folder named `docs` will be created in your root directory. Just open `index.html` in your browser to see if your like it or not.
