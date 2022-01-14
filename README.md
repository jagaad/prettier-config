# `@jagaad/prettier-config`

> Jagaad personal [Prettier](https://prettier.io) config.

## Usage

**Install**:

```shell
npm install --dev @jagaad/prettier-config
```

- **Add to `package.json`**:

```jsonc
{
  // ...
  "prettier": "@jagaad/prettier-config"
}
```

- **Add to `.prettierrc.json`**:

```json
"@jagaad/prettier-config"
```

- **Add to `.prettierrc.js`**:

```js
module.exports = {
  ...require("@jagaad/prettier-config"),
  // ...
};
```