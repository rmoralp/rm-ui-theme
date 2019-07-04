# rm-ui-theme

This repository contains:

* Generic variables to initialize default values.
* Functions and mixins helpers.

## Usage

Import `rm-ui-theme` into your component, or SPA including the path in `index.scss`:

```
@import '~@rmoral/theme/lib/index';
```

If you want to customize some variables, create your own theme and add it to your main scss just __before__ the `rm-ui-theme` import.

```
@import './custom-theme';
@import '~@rmoral/theme/lib/index';
```

## Update

If you need to update any of these variables please pull request.

## Inspired on

[@schibstedspain/sui-theme](https://github.com/SUI-Components/sui-theme)