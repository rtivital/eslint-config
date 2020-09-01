# @rtivital/eslint-config

Prettier and ESlint configuration I use for the majority of react projects. It is based on airbnb config with some rules tweaks.

## Installation

```sh
npx install-peerdeps --dev @rtivital/eslint-config
```

## Usage

Example usage (see [omatsuri](https://github.com/rtivital/omatsuri) for full usage):

```js
// .eslintrc.js
module.exports = {
  extends: ['@rtivital/eslint-config'],
  rules: {
    /* override rules */
  },
};

// .prettierrc.js
module.exports = require('@rtivital/eslint-config/.prettierrc');
```
