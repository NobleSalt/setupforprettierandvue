## Add this inside package.json

```json

  "prettier": {
    "singleQuote": true,
    "semi": false,
    "trailingComma": "none",
    "bracketSpacing": true
  }
```

## Add this inside .eslintrc.js

```js

  rules: {
    'space-before-function-paren': [
      'error',
      {
        anonymous: 'never',
        named: 'never',
        asyncArrow: 'never'
      }
    ]
  }
```

## Add this inside .vscode/settings.json

```json
{
  "editor.tabSize": 2,
  "editor.autoIndent": "full",
  "editor.detectIndentation": true,
  "prettier.singleQuote": true,
  "vetur.format.defaultFormatterOptions": {
    "js-beautify-html": {
      "wrap_attributes": "force-expand-multiline"
    },
    "prettyhtml": {
      "printWidth": 100,
      "singleQuote": false,
      "wrapAttributes": false,
      "sortAttributes": false
    },
    "prettier": {
      "singleQuote": true,
      "semi": false
    }
  },
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true
}
```
