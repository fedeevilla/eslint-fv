# Eslint Config

## Install

```shell
npm install eslint-fv
```

Afterwards, you should create a configuration file .eslintrc.js in the root of the project and copy the following code:

```javascript
module.exports = {
  extends: ["./node_modules/eslint-fv/.eslintrc.js"],
};
```
