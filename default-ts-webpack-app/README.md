# `default-ts-webpack-app`

#### Disclaimer: For this project the usual `au build` and `au run` may not produce desired results due to the change in `webpack.config.js`

This project is bootstrapped by [aurelia-cli](https://github.com/aurelia/cli).

For more information, go to https://aurelia.io/docs/cli/webpack

## Run dev app

Run ~~`au run`~~ `npm start`, then open `http://localhost:8080`

~~To open browser automatically, do `au run --open`.~~

~~To change dev server port, do `au run --port 8888`.~~

You can still change the standard webpack configurations from CLI easily with something like this: `npm start -- --open --port 8888`. If you have settled from your fling, change the `npm start` script with the new arguments, and you are back to the comfort of `npm start`.

To enable Webpack Bundle Analyzer, do ~~`au run --analyze`~~ `npm run analyze` (for development build) or `npm run analyze -- --env.production` (for production build).

~~To enable hot module reload, do `au run --hmr`.~~ HMR is enabled by default by `npm start`, if that does not float your boat or your elements are not reloaded correctly, then remove `--env.hmr` flag from `npm start` script.

## Build for... 

### ... production ...

Run ~~`au build --env prod`~~ `npm run build`.

### ... or development

Run `npm run build:dev`

## Unit tests

Run `au test` (or `au jest`).

To run in watch mode, `au test --watch` or `au jest --watch`.
