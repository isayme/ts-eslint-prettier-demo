# 示例配置项目: Typescript + ESLint + Prettier + EditorConfig

EditorConfig 使用配置: https://github.com/isayme/editorconfig

Prettier 使用配置: [@isayme/prettier-config](https://www.npmjs.com/package/@isayme/prettier-config)

ESLint 使用配置: [@isayme/eslint-config](https://www.npmjs.com/package/@isayme/eslint-config)

VSCode 关键配置:

```
  # 禁用自动保存
  "editor.formatOnSave": false,
  # 使用此配置触发自动保存
  "editor.codeActionsOnSave": [
    "source.addMissingImports",
    "source.organizeImports",
    "source.fixAll.format",
    "source.fixAll.eslint"
  ],
  # 是的配置对 typescript 有效
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
```
