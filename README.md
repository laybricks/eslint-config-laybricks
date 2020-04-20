# eslint-config-laybricks

## How to set

1. Add following line to `.vscode/setting.json` file

```json
{
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "[javascript, typescript]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint",
    "eslint.alwaysShowStatus": true,
    "eslint.validate": ["javascript", "typescript"]
  },
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true
}
```

2. Install prettier and eslint extension in vscode
- [esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

3. Add following line to project's `package.json` file

```json
{
  "eslintConfig": {
    "extends": "eslint-config-laybricks"
  },
  "prettier": "eslint-config-laybricks/prettier.config",
}
```

4. Done! Just start coding and have fun.💜❤️💛
