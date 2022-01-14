# `@jagaad/prettier-config`

> Jagaad personal [Prettier](https://prettier.io) config.

This config is based on a [poll](https://forms.gle/uS6tihGf6kp2UMRR7) that was voted inside company.

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