#Import map overview

Currently this example only works in WebKit. Let's hope that sooner or later this technology will have future.

## Propousel documentation
* https://wicg.github.io/import-maps/
* https://github.com/WICG/import-maps


## Can i use
* https://caniuse.com/import-maps

## Ppolyfills and tooling
* [@import-maps/resolve](https://www.npmjs.com/package/@import-maps/resolve) resolves a specifier relative to an import map.
* [@jsenv/node-module-import-map](https://www.npmjs.com/package/@jsenv/node-module-import-map) generates an import map from your `package.json` and `node_modules/` directories.
* [@jsenv/importmap-eslint-resolver](https://www.npmjs.com/package/@jsenv/importmap-eslint-resolver) enables import map resolution in [ESLint](https://eslint.org/)
* [@node-loader/import-maps](https://www.npmjs.com/package/@node-loader/import-maps) is a [Node.js loader](https://nodejs.org/dist/latest/docs/api/esm.html#esm_experimental_loaders) for using import maps in Node.js.
* [@web/dev-server-import-maps](https://www.npmjs.com/package/@web/dev-server-import-maps) allows using import maps during development and testing with [@web/dev-server](https://www.npmjs.com/package/@web/dev-server) and [@web/test-runner](https://www.npmjs.com/package/@web/test-runner).
* [Deno](https://github.com/denoland/deno) is a JavaScript/TypeScript runtime with [built-in support for import maps](https://deno.land/manual/linking_to_external_code/import_maps).
* [es-module-shims](https://github.com/guybedford/es-module-shims) provides an import maps polyfill for browsers with basic ES modules support.
* [import-map-deployer](https://github.com/single-spa/import-map-deployer) is designed for updating import map files from CI
* [import-map-overrides](https://www.npmjs.com/package/import-map-overrides) allows using import maps to improve development flow by pointing to local versions.
* [importly](https://www.npmjs.com/package/importly) generates an import map from a `package.json`.
* [SystemJS](https://github.com/systemjs/systemjs) provides a polyfill-like workflow for using import maps in older browsers with the System module format and `<script type="systemjs-importmap">`.
* [webpack-import-map-plugin](https://www.npmjs.com/package/webpack-import-map-plugin) generates import maps for the output of [webpack](https://webpack.js.org/), especially useful for the [hashing use case](#mapping-away-hashes-in-script-filenames).
