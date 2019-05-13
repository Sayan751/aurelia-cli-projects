# `custom-ts-webpack-app`

This project is bootstrapped by [aurelia-cli](https://github.com/aurelia/cli), specifically using below command

```bash
au new custom-ts-webpack-app --unattended --select typescript,htmlmin-max,protractor,vscode,scaffold-navigation
```

For more information, go to https://aurelia.io/docs/cli/webpack

## Run dev app

Run `au run`, then open `http://localhost:8080`

To open browser automatically, do `au run --open`.

To change dev server port, do `au run --port 8888`.

To enable Webpack Bundle Analyzer, do `au run --analyze`.

To enable hot module reload, do `au run --hmr`.

## Build for production

Run `au build --env prod`.

## Unit tests

Run `au test` (or `au karma`).

To run in watch mode, `au test --watch` or `au karma --watch`.

## Integration (e2e) tests

You need the app running for integration test.

First, run `au run` and keep it running.

Then run `au protractor`.