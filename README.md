## Setup

```bash
$ npm install
```

## Run development mode with hot reload

```bash
$ npm run dev
```

## Run build

```bash
$ npm run build
```

Compiled code will be in `./server/public/dist/` folder.

## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

We set `NPM_CONFIG_PRODUCTION` to `false` to install `devDependencies`

```bash
$ heroku config:set NPM_CONFIG_PRODUCTION=false
```
