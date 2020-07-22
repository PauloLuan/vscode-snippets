# reativa-snippets

[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2FPauloLuan%2Fvscode-snippets%2Fbadge%3Fref%3Dmaster&style=for-the-badge)](https://actions-badge.atrox.dev/PauloLuan/vscode-snippets/goto?ref=master)

[code]: https://code.visualstudio.com/

## Test Snippets

Below is a list of all available snippets and the triggers of each one. The **→** means the `TAB` key.

### Globals

|  Trigger | Content       |
| -------: | ------------- |
|  `desc→` | describe      |
| `desco→` | describe.only |
| `descs→` | describe.skip |
| `desce→` | describe.each |
|    `ae→` | after each    |
|    `aa→` | after all     |
|    `be→` | before each   |
|    `ba→` | before all    |

### Tests

| Trigger | Content            |
| ------: | ------------------ |
|   `it→` | it                 |
|  `ito→` | it.only            |
|  `its→` | it.skip            |
|  `itt→` | it.todo            |
|  `ite→` | it.each            |
|  `ita→` | it(..., async ...) |
| `test→` | test.each          |

### Expect

| Trigger | Content |
| ------: | ------- |
|  `exp→` | expect  |
|   `tb→` | toBe    |
|   `te→` | toEqual |

### Javascript ES6 Snippets:

### Import and export

| Trigger | Content                                                                                                |
| ------: | ------------------------------------------------------------------------------------------------------ |
|  `imp→` | imports entire module `import fs from 'fs';`                                                           |
|  `imn→` | imports entire module without module name `import 'animate.css'`                                       |
|  `imd→` | imports only a portion of the module using destructing `import {rename} from 'fs';`                    |
|  `ime→` | imports everything as alias from the module `import * as localAlias from 'fs';`                        |
|  `ima→` | imports only a portion of the module as alias `import { rename as localRename } from 'fs';`            |
|  `rqr→` | require package `require('');`                                                                         |
|  `req→` | require package to const `const packageName = require('packageName');`                                 |
|  `mde→` | default module.exports `module.exports = {};`                                                          |
|  `env→` | exports name variable `export const nameVariable = localVariable;`                                     |
|  `enf→` | exports name function `export const log = (parameter) => { console.log(parameter);};`                  |
|  `edf→` | exports default function `export default function fileName (parameter){ console.log(parameter);};`     |
|  `ecl→` | exports default class `export default class Calculator { };`                                           |
|  `ece→` | exports default class by extending a base one `export default class Calculator extends BaseClass { };` |

### Class helpers

| Trigger | Content                                                        |
| ------: | -------------------------------------------------------------- |
|  `con→` | adds default constructor in the class `constructor() {}`       |
|  `met→` | creates a method inside a class `add() {}`                     |
|  `pge→` | creates a getter property `get propertyName() {return value;}` |
|  `pse→` | creates a setter property `set propertyName(value) {}`         |

### Various methods

|  Trigger | Content                                                                               |
| -------: | ------------------------------------------------------------------------------------- |
|   `fre→` | forEach loop in ES6 syntax `array.forEach(currentItem => {})`                         |
|   `fof→` | for ... of loop `for(const item of object) {}`                                        |
|   `fin→` | for ... in loop `for(const item in object) {}`                                        |
|  `anfn→` | creates an anonymous function `(params) => {}`                                        |
|   `nfn→` | creates a named function `const add = (params) => {}`                                 |
|   `dob→` | destructing object syntax `const {rename} = fs`                                       |
|   `dar→` | destructing array syntax `const [first, second] = [1,2]`                              |
|   `sti→` | set interval helper method `setInterval(() => {});`                                   |
|   `sto→` | set timeout helper method `setTimeout(() => {});`                                     |
|  `prom→` | creates a new Promise `return new Promise((resolve, reject) => {});`                  |
| `thenc→` | adds then and catch declaration to a promise `.then((res) => {}).catch((err) => {});` |

### Console methods

| Trigger | Content                                                            |
| ------: | ------------------------------------------------------------------ |
|  `cas→` | console alert method `console.assert(expression, object)`          |
|  `ccl→` | console clear `console.clear()`                                    |
|  `cco→` | console count `console.count(label)`                               |
|  `cdb→` | console debug `console.debug(object)`                              |
|  `cdi→` | console dir `console.dir`                                          |
|  `cer→` | console error `console.error(object)`                              |
|  `cgr→` | console group `console.group(label)`                               |
|  `cge→` | console groupEnd `console.groupEnd()`                              |
|  `clg→` | console log `console.log(object)`                                  |
|  `clo→` | console log object with name `console.log('object :>> ', object);` |
|  `ctr→` | console trace `console.trace(object)`                              |
|  `cwa→` | console warn `console.warn`                                        |
|  `cin→` | console info `console.info`                                        |
|  `clt→` | console table `console.table`                                      |
|  `cti→` | console time `console.time`                                        |
|  `cte→` | console timeEnd `console.timeEnd`                                  |

## Settings

The `editor.snippetSuggestions` setting in vscode `settings.json` will show snippets on top of the suggestion list.

```json
"editor.snippetSuggestions": "top"
```

## Credits

Heavily inspired on / thanks to:

- [andys8](https://github.com/xabikos) for [vscode-jest-snippets](https://github.com/andys8/vscode-jest-snippets)
- [xabikos](https://github.com/xabikos) for [vscode-javascript](https://github.com/xabikos/vscode-javascript)
