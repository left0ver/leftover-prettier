我的prettier配置

# Install

```shell
npm i leftover-prettier -D

// or 

yarn add leftover-prettier -D
```

# Usage

```json

//  package.json
{
  // ...
  "prettier":"leftover-prettier"
}

```

or

```javascript
// .prettierrc.js
module.exports = {
  ...require("leftover-prettier"),
};
```
# 配置项

```json
{
  "printWidth": 80,
  "singleQuote": true,
  "trailingComma": "all",
  "endOfLine": "lf",
  "semi":false,
  "bracketSpacing":true,
  "bracketSameLine":true,
  "jsxBracketSameLine":true,
  "arrowParens":"avoid",
  "embeddedLanguageFormatting":"off"
}

```


