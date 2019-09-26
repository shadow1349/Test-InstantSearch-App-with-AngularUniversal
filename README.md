# Test InstantSearchApp

After installing `node_modules` run `npm run build:ssr`. Once that command has completed then run `npm run serve:ssr` and you will get the following error:

```
TestInstantSearchApp/node_modules/angular-instantsearch/node_modules/instantsearch.js/es/index.js:2
import algoliasearchHelper from 'algoliasearch-helper';
       ^^^^^^^^^^^^^^^^^^^

SyntaxError: Unexpected identifier
    at Module._compile (internal/modules/cjs/loader.js:721:23)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:787:10)
    at Module.load (internal/modules/cjs/loader.js:653:32)
    at tryModuleLoad (internal/modules/cjs/loader.js:593:12)
    at Function.Module._load (internal/modules/cjs/loader.js:585:3)
    at Module.require (internal/modules/cjs/loader.js:690:17)
    at require (internal/modules/cjs/helpers.js:25:18)
    at algoliasearchProxy__default (TestInstantSearchApp/node_modules/angular-instantsearch/bundles/angular-instantsearch.umd.js:2:170)
    at Object.<anonymous> (TestInstantSearchApp/node_modules/angular-instantsearch/bundles/angular-instantsearch.umd.js:5:2)
    at Module._compile (internal/modules/cjs/loader.js:776:30)
```
