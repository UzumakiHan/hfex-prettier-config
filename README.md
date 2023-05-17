# prettier-config

这个包定义使用 Prettier 代码修复时所设定的规则。

## 使用方法

```bash
npm i hfex-prettier-config prettier -D
```

在 package.json 中配置

```json
{
    "scripts": {
        "prettier": "prettier ./src/*/**/* --write"
    },
    "prettier": "hfex-prettier-config",
}
```

运行
```bash
npm run prettier
```
