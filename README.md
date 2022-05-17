# @nerkarso/eslint-config

ESLint configuration.

## Installation

```sh
npm install -D https://github.com/nerkarso/eslint-config.git
```

## Usage

Add it to the `extends` property in your **package.json** file.

```json
{
  ...
  "eslintConfig": {
    "extends": [
      "@nerkarso/eslint-config/react"
    ]
  }
}
```

Or in your **.eslintrc.json** file.

```json
{
  "extends": ["@nerkarso/prettier-config/react"],
  ...
}
```

## License

[MIT](LICENSE)
