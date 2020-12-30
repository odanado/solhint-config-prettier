# solhint-config-prettier

Disable rules that may conflict with [solhint](https://github.com/protofire/solhint) and [Prettier](https://github.com/prettier/prettier).

## Installation

```console
npm install --save-dev solhint-config-prettier
```

## Configuration
Add solhint-config-prettier to `extends` in `.solhint.json`.

```json
{
  "extends": [
    "solhint:default",
    "prettier"
  ]
}
```