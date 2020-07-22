# reativa-snippets

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

## Settings

The `editor.snippetSuggestions` setting in vscode `settings.json` will show snippets on top of the suggestion list.

```json
"editor.snippetSuggestions": "top"
```

## Credits

Heavily inspired on / thanks to:

- [andys8](https://github.com/xabikos) for [vscode-jest-snippets](https://github.com/andys8/vscode-jest-snippets)
- [xabikos](https://github.com/xabikos) for [vscode-javascript](https://github.com/xabikos/vscode-javascript)
