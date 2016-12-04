# eslint-config-eshinse-react-native

Configuration:

* Enables JSX
* React Native related rules.

Peer dependencies:

* [eslint-plugin-react-native](https://github.com/intellicode/eslint-plugin-react-native)

## Install

`npm install --save-dev eslint-config-eshinse-react-native`

## Use

The order of the extensions matter; each additional configuration extends the preceding configurations.

**.eslintrc.yaml:**

```
---

extends:
  - eshinse
  - eshinse-jsdoc
  - eshinse-react
  - eshinse-react-native
```

**.eslintrc.json:**

```json
{
  "extends": [
    "eshinse",
    "eshinse-jsdoc",
    "eshinse-react",
    "eshinse-react-native"
  ]
}
```

## Licence (Apache-2.0)

See [LICENCE](LICENCE).

## Additional ESLint configs

* [eslint-config-eshinse](https://github.com/eshinse/eslint-config-eshinse)
* [eslint-config-eshinse-jsdoc](https://github.com/eshinse/eslint-config-eshinse-jsdoc)
* [eslint-config-eshinse-react](https://github.com/eshinse/eslint-config-eshinse-react)
