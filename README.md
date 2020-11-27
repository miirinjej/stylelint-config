# @miirinjej/stylelint-config

[![npm version](https://img.shields.io/npm/v/@miirinjej/stylelint-config.svg)](https://www.npmjs.org/package/@miirinjej/stylelint-config)

> Sharable stylelint config for CSS/SCSS

## Installation

```
npm install --save-dev @miirinjej/stylelint-config stylelint
```

## Usage

Add this config to `package.json`:

```yaml
"stylelint": {
  "extends": "@miirinjej/stylelint-config"
}
```

See also: [https://stylelint.io/user-guide/configure](https://stylelint.io/user-guide/configure)

### Extending the config

You can extend the current configuration by overriding rules or an array of existing configurations:

```yaml
{
  "extends": ["@miirinjej/stylelint-config", "./stylelint.config.js"],
  "rules": {
    "indentation": "tab"
  }
}
```

See also: [https://stylelint.io/user-guide/configure#extends](https://stylelint.io/user-guide/configure#extends)

## Extensions

- [stylelint-config-recess-order](https://github.com/stormwarning/stylelint-config-recess-order) — A Stylelint config that sorts CSS properties the way Recess did and Bootstrap did/does.
- [stylelint-scss](https://github.com/kristerkari/stylelint-scss) — A collection of SCSS specific linting rules for 
  stylelint.

## Rules

See [config](https://github.com/miirinjej/stylelint-config/blob/master/index.js) itself.

Rules are grouped and sorted by default as in the original lists:

- [stylelint](https://stylelint.io/user-guide/rules/list)
- [stylelint-scss](https://github.com/kristerkari/stylelint-scss#list-of-rules)
