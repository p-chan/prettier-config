# prettier-config

> [@p-chan](https://github.com/p-chan)'s [Prettier](https://prettier.io/) config

## Usage

Install

```bash
$ npm install @p-chan/prettier-config --save-dev
```

Edit `package.json`

```jsonc
{
  // ...
  "prettier": "@p-chan/prettier-config"
}
```

or edit `.prettierrc.js`

```js
module.exports = {
  ...require("@p-chan/prettier-config")
};
```

## Override

```js
module.exports = {
  ...require("@p-chan/prettier-config"),
  singleQuote: false,
  semi: true
};
```

---

Inspired by [azz/prettier-config](https://github.com/azz/prettier-config)
