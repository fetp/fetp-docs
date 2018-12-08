# ESLint Standard Configuration

Use for `FETP` 

## Style

- [JavaScript Standard Style](https://standardjs.com/)
- [eslint-plugin-vue essential](https://github.com/vuejs/eslint-plugin-vue#priority-a-essential-error-prevention)

## Usage

`package.json` eslint configuration

```json
{
  "eslintConfig": {
    "extends": "@fetp/eslint-config-fetp"
  },
  "eslintIgnore": [
    "/dev",
    "/output"
  ]
}
```

Optional

- standard（FETP）：`@fetp/eslint-config-fetp`

## Combined editor

Install Golbal Dependence

```bash
npm i -g eslint @yy/eslint-config-fe eslint-plugin-import eslint-plugin-node eslint-plugin-promise eslint-config-standard eslint-plugin-standard eslint-plugin-vue@next babel-eslint eslint-plugin-react eslint-config-standard-react
```

### VS Code

Install Extends

- ESLint：https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
- EditorConfig：https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig

Configuration

```json
{
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    { "language": "vue", "autoFix": true },
    { "language": "html", "autoFix": true }
  ]
}
```
