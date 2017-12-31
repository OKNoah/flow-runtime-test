This is just an example of a configuration that isn't working.

```
> node --version
v8.9.1
```

```
/Users/noah/Projects/flow-runtime-test/index.js:1
(function (exports, require, module, __filename, __dirname) { import t from 'flow-runtime';
                                                              ^^^^^^

SyntaxError: Unexpected token import
    at createScript (vm.js:80:10)
    at Object.runInThisContext (vm.js:139:10)
    at Module._compile (module.js:599:28)
    at loader (/Users/noah/Projects/flow-runtime-test/node_modules/babel-register/lib/node.js:144:5)
    at Object.require.extensions.(anonymous function) [as .js] (/Users/noah/Projects/flow-runtime-test/node_modules/babel-register/lib/node.js:154:7)
    at Module.load (module.js:554:32)
    at tryModuleLoad (module.js:497:12)
    at Function.Module._load (module.js:489:3)
    at Function.Module.runMain (module.js:676:10)
    at startup (bootstrap_node.js:187:16)
[nodemon] app crashed - waiting for file changes before starting...
```