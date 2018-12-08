# ESLint 配置标准

给 `FETP` 项目使用。其他项目也可以使用。

## 主要风格

- [JavaScript Standard Style](https://standardjs.com/)
- [eslint-plugin-vue essential](https://github.com/vuejs/eslint-plugin-vue#priority-a-essential-error-prevention)

## 配置使用

在项目的 `package.json` 文件中配置。

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

可选配置：

- 标准（FETP）：`@fetp/eslint-config-fetp`

## 结合编辑器使用

安装全局环境依赖。

```bash
npm i -g eslint @yy/eslint-config-fe eslint-plugin-import eslint-plugin-node eslint-plugin-promise eslint-config-standard eslint-plugin-standard eslint-plugin-vue@next babel-eslint eslint-plugin-react eslint-config-standard-react
```

### VS Code

安装扩展。

- ESLint：https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
- EditorConfig：https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig

配置。

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
