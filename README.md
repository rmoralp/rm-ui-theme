# rm-ui-theme

This repository contains:

* Generic variables to initialize default values and component styles.
* Functions and mixins helpers.

## Usage

Import `rm-ui-theme` into your sui-component including the path in `index.scss`:

```
@import '../node_modules/@rm/theme/lib/index';
```

If you want to customize your components, create your own theme and add it to your component just __before__ the sui-theme import.

```
@import '../custom-settings';
@import '~@rm/theme/lib/index';
```

## Update
If you need to update any of these variables please pull request.

## Inspired on

[@schibstedspain/sui-theme](https://github.com/SUI-Components/sui-theme)