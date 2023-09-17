# BNP ESLint config for React

Configs for React only

## Setup

1 - Install as a dev dependencie

```terminal
  npm i -D bnp-eslint-and-prettier-config
```

2 - Create a `.eslintrc.json` file extending the config:

```json
{
	"extends": "bnp-eslint-and-prettier-config/reactEslint.js"
	// In NextJs project: "extends": ["next/core-web-vitals", "bnp-eslint-and-prettier-config/reactEslint.js" ]
}
```

3 - Create a `.prettierrc.js` file extending the config:

```js
module.exports = {
	...require("bnp-eslint-and-prettier-config/reactPrettier"),
	// Your another configs
};
```
