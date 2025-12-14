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

```jsonc
{
  "oxc.typeAware": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.oxc": "always"
  },
}
```

You might also want to add the following script withing your `package.json`:

```jsonc
{
  // …
  "scripts": {
    // …
    "lint": "oxlint --type-aware"
  }
}
```

## Formatter

Install

```bash
pnpm i -D oxfmt
```

You might want to set the following within your `.vscode/settings.json` file:

```jsonc
{
  "editor.defaultFormatter": "oxc.oxc-vscode",
  "oxc.fmt.experimental": true,
}
```

You might also want to add the following script withing your `package.json`:

```jsonc
{
  // …
  "scripts": {
    // …
    "format": "oxfmt"
  }
}
```