# @yungezeit/oxc-config

> **Warning**
> This repository is not distributed as a package

This repository gathers a collection of pre-defined OXC configurations.


## Linter

Install

```bash
pnpm i -D oxlint oxlint-tsgolint
```

You might want to set the following within your `.vscode/settings.json` file:

```json
{
  "oxc.typeAware": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.oxc": "always"
  },
}
```


## Formatter

```bash
pnpm i -D oxfmt
```

You might want to set the following within your `.vscode/settings.json` file:

```json
{
  "editor.defaultFormatter": "oxc.oxc-vscode",
  "oxc.fmt.experimental": true,
}
```