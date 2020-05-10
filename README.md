# prettier-config

> Shared Prettier config for [@p-chan](https://github.com/p-chan)

## Install

```bash
$ npm install @p-chan/prettier-config --save-dev
```

## Usage

Edit `.prettierrc.js`.

```js
module.exports = {
  ...require('@p-chan/prettier-config'),
}
```

## Override

```js
module.exports = {
  ...require('@p-chan/prettier-config'),
  singleQuote: false,
  semi: true,
}
```

## Author

[@p-chan](https://github.com/p-chan)

## License

MIT

---

Inspired by [azz/prettier-config](https://github.com/azz/prettier-config)
