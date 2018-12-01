# tassilogroeper.de

Personal website.

## Deploy

```bash
$ yarn deploy-git-ftp
```

Then bitbucket pipelines will take over.

### Installation

```bash
$ yarn
```

### Start Dev Server

```bash
$ yarn start
```

### Build Prod Version

```bash
$ yarn build
```

### Features:

* ES6 Support via [babel](https://babeljs.io/) (v7)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)

When you run `yarn build` we use the [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) to move the css to a separate file. The css file gets included in the head of the `index.html`.
