# Release

## Install `vsce`

```shell
npm i -g vsce
```

## Publish

- Bump version in `package.json`
- [Create release on github](https://github.com/PauloLuan/vscode-snippets/releases/new)
- Run `npm run publish` or `vsce publish`

## Create a token

<https://PauloLuan.visualstudio.com/_usersSettings/tokens>
with custom defined scope "Marketplace"

### Login

```shell
vsce login pauloluan
```
