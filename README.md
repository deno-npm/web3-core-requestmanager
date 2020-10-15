# web3-core-requestmanager

[![NPM Package][npm-image]][npm-url] [![Dependency Status][deps-image]][deps-url] [![Dev Dependency Status][deps-dev-image]][deps-dev-url]

This is a sub-package of [web3.js][repo].

This requestmanager package is used by most [web3.js][repo] packages.

Please read the [documentation][docs] for more.

## Usage

```js
import Web3WsProvider from "https://deno.land/x/npm_web3_providers_ws@0.0.1/mod.js";
import Web3RequestManager from "https://deno.land/x/npm_web3_core_requestmanager@0.0.1/mod.js";

const requestManager = new Web3RequestManager(new Web3WsProvider('ws://localhost:8546'));
```

[docs]: http://web3js.readthedocs.io/en/1.0/
[repo]: https://github.com/ethereum/web3.js
[npm-image]: https://img.shields.io/npm/v/web3-core-requestmanager.svg
[npm-url]: https://npmjs.org/package/web3-core-requestmanager
[deps-image]: https://david-dm.org/ethereum/web3.js/1.x/status.svg?path=packages/web3-core-requestmanager
[deps-url]: https://david-dm.org/ethereum/web3.js/1.x?path=packages/web3-core-requestmanager
[deps-dev-image]: https://david-dm.org/ethereum/web3.js/1.x/dev-status.svg?path=packages/web3-core-requestmanager
[deps-dev-url]: https://david-dm.org/ethereum/web3.js/1.x?type=dev&path=packages/web3-core-requestmanager

