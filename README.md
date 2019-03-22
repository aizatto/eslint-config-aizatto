
[![Greenkeeper badge](https://badges.greenkeeper.io/aizatto/eslint-config-aizatto.svg)](https://greenkeeper.io/)

f"fRun:
```
yarn add "https://github.com/aizatto/eslint-config-aizatto#"
```

Then:

```
yarn run eslint -- --init
```

In your `.eslintrc.js`:

```js
module.exports = {
  parser: "babel-eslint",
  extends: [
    "airbnb",
    "aizatto",
  ]
};
```
