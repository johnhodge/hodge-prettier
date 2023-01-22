# @johnhodge/prettier-config

The Prettier config used by John.

## Install

NPM

```zsh
npm install @johnhodge/prettier-config --save-dev
```

Yarn

```zsh
yarn add --dev @johnhodge/prettier-config
```

## Configure

Include this at the top of the `package.json` file:

```json
{
  "name": "some-project",
  "prettier": "@johnhodge/prettier-config"
}
```

Alternatively, you can add this to `.prettierrc.js`:

```js
module.exports = {
  ...require("@johnhodge/prettier-config"),
};
```

Using the `.prettierrc.js` implementation is recommended since it allows you to extend the prettier config.
