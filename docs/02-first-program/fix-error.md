# コードのエラーを修正する

```js
function main() {
    console.log("Today is sunny!);
}
```
```
/workspace/Main.js:5
    console.log("Today is sunny!)
                ^^^^^^^^^^^^^^^^^

SyntaxError: Invalid or unexpected token
    at Object.compileFunction (node:vm:360:18)
    at wrapSafe (node:internal/modules/cjs/loader:1055:15)
    at Module._compile (node:internal/modules/cjs/loader:1090:27)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1180:10)
    at Module.load (node:internal/modules/cjs/loader:1004:32)
    at Function.Module._load (node:internal/modules/cjs/loader:839:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:81:12)
    at node:internal/main/run_main_module:17:47
```
```js
function main() {
    console.log("Today is sunny!");
}
```
```
Today is sunny!
```
